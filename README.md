# Hi, I'm Wonsok Choi

**AI Product / Agent Engineer.** I ship production software with agentic development
workflows, and I research **ask-first, trust-aware memory systems** on the side.

I build AI products that learn from user data **without pretending guesses are facts**.

## Now (2026)

### Jion — Founding Engineer, Backend & AI Product
Building **Shop Manager**, a multi-channel order management SaaS for Korean e-commerce sellers.
Live in beta with real sellers since mid-2026.

- Sole backend owner: FastAPI service, versioned `/v1` API consumed by a separate web team
- Channel integrations (Cafe24, Ably, more in progress), carrier shipping API (CJ), auth (Clerk)
- Order lifecycle: collection → packing → labeling → shipment → claims, with per-channel lifecycle contracts
- Deploy & ops on a small OCI VM (Terraform, systemd), 360+ commits since 2026-07

### Socra AI — ML Engineer
Also working as an ML Engineer at **Socra AI**(Riiid).

### wondoritos — side company experiment
A one-person "AI-run company": Claude agents build, ship and market small apps
(first app: **copyism**), synced across a dev MacBook and an always-on Mac mini.
→ [wondoritos.com](https://github.com/wondollchoi/wondoritos.com)

## How I work with agents

Most of the code above is written by AI worker sessions, not by hand.

- **Orchestrator / worker split** — I plan, review and merge; worker sessions write code on branches
- **PR as the decision gate** — parallel workers, one explicit merge decision
- **Verify by state, not by output** — deploys and migrations are checked against the real system, not logs
- **Evidence before assertion** — no feature ships on an assumed API; every channel adapter starts from live captures

Lessons from this feed back into [wondoll-harness](https://github.com/wondollchoi/wondoll-harness).

## Research & side projects

- **memory-weaver** (private, commercial alpha) — an ask-first personal memory AI that starts with a gallery,
  learns through conversation, and helps users remember life better.
  Chat-primary, graph-amplified; question / confirm / organize loop.
- **gallery-agent-oss** (private) — a local-first gallery AI curator that proposes people / events / intent
  candidates and stores only what the user confirms. Trust model: **Observed → Inferred → Confirmed → Authored**.
- [wondoll-harness](https://github.com/wondollchoi/wondoll-harness) — self-developing agent harness:
  Planner → Builder → Evaluator → Trust → E2E gate, JSON-schema eval manifests.
- [wonbot](https://github.com/wondollchoi/wonbot) — always-on autonomous multi-agent system on a Mac mini:
  CEO–CFO governance, ChromaDB semantic memory, Telegram ops loop.

## Design principles

- **Ask before you assume**
- **Evidence before assertion**
- **Quiet by default**
- **Explicit permission over silent automation**
- **Human-in-the-loop for meaningful actions**

## Long-term north star

I'm interested in systems that act **less like a digital twin** and more like a
**careful curator of a person's memories**.

> How do we build a memory system that helps a person — or a family — preserve, search,
> update, and revisit a life archive across photos, voice, text, video, and documents?

## Background

- Research: vector DB / ANN indexing, RAG retrieval effectiveness, multimodal AI experiments
- [web3-sns](https://github.com/wondollchoi/web3-sns) — blockchain NFT social platform, graduation thesis (Ethereum Sepolia)

## Contact

- Email: `cws990828@gmail.com`
- GitHub: `github.com/wondollchoi`
