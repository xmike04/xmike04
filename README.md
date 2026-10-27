# Michael Marin — Applied AI & ML Engineer

I build applied AI systems at the point where machine learning meets a product people can test, evaluate, and use. My strongest evidence is in retrieval engineering and evaluation, real-time computer vision, LLM system boundaries, AI product evaluation, and cloud engineering.

I am pursuing an **M.S. in Artificial Intelligence (Machine Learning concentration)** at the University of North Texas, expected **Summer 2027**, after earning a **B.S. in Computer Science** from UNT in May 2025. I am seeking **AI/ML and applied-AI internships and co-ops**.

[Claim-to-evidence ledger](https://github.com/xmike04/xmike04.github.io/blob/40dbf49a533e49418dfd1636e073970b22a7538f/docs/evidence/claims.md)

## Evidence

- **Retrieval engineering and evaluation:** Built [RAGOps](https://github.com/xmike04/RAG_OPS), a FastAPI/PostgreSQL/pgvector/Redis platform with asynchronous ingestion, RRF, metrics, and a React operations console. Its separate offline SciFact experiment used 5,183 documents and 300 held-out queries: RRF achieved 0.8059 Recall@10 and 0.6816 nDCG@10. The serving application uses PostgreSQL cover-density lexical ranking and sequential retrieval. A [controlled mixed-query local-provider matrix](https://github.com/xmike04/RAG_OPS/blob/5549d6792a6f5f4c6126c41deb9f1e16ec5e9264/benchmarks/service/results/load/2026-10-26-local-40389341425/README.md) completed 300 requests each at concurrency 1/4/8 with p95 54.73/137.22/252.24 ms and no measured failures; generation was excluded. The experimental cross-encoder reduced held-out quality and remains a negative result. The [separate serving-path baseline](https://github.com/xmike04/RAG_OPS/blob/df271a5bf9adc8c610fa8ba19f18cedea6c7ee5e/benchmarks/service/results/scifact/2026-10-26-local-40380993127/README.md) measures the actual application with matching deterministic providers. [Sources, configurations, and limits](https://github.com/xmike04/xmike04.github.io/blob/40dbf49a533e49418dfd1636e073970b22a7538f/docs/evidence/claims.md#ragops-retrieval).
- **AI product evaluation:** Worked as a Product Analyst Intern on Mr. Cooper Group's AI/ML team in 2025, supporting agentic-AI customer-service products through experimentation, user validation, feature evaluation, and cross-functional delivery.
- **Computer vision leadership:** As Lead Developer for the five-person **UNT senior capstone (Fall 2024–May 2025)**, co-designed fuzzy-logic gestures, built the ImGui hardware-setup interface, and connected and oversaw Unity integration for NASA PACE **WAVE: From Space to Ocean**. The team system linked ZED tracking and gesture scores to Unity through OSC. We met regularly with NASA PACE collaborators and coordinated with University of Maryland partners; the installation premiered at the Kennedy Center in March 2025. [Personal contribution scope](https://github.com/xmike04/xmike04.github.io/blob/40dbf49a533e49418dfd1636e073970b22a7538f/docs/evidence/claims.md#nasa-role).
- **LLM systems:** Built [SIMLYFE](https://github.com/xmike04/SIMLYFE), a life simulator separating deterministic game logic from authenticated, schema-validated event generation. [CI on October 26, 2026](https://github.com/xmike04/SIMLYFE/actions/runs/40454214650) passed 789 Vitest test cases across 38 files plus controlled desktop/mobile browser flows. Diagnosed and repaired a Nano completion-budget truncation; the original Guest then generated and resolved five events at ages 6–10 and restored age 10 after reload. This bounded check does not establish a reliability SLO, broad narrative quality, cost or cross-device recovery. [Current canary evidence](https://github.com/xmike04/SIMLYFE/blob/d851546883a84bee28ac0c0dcd0f2a44eef7d20b/docs/operations.md#original-guest-reached-age-10-after-the-repair).
- **Cloud engineering:** Owner-confirmed **AWS Certified Machine Learning — Specialty** and **Google Cloud Certified Professional Cloud Architect** certifications. Public credential links and independent current-validity verification are unavailable; [verification limits](https://github.com/xmike04/xmike04.github.io/blob/40dbf49a533e49418dfd1636e073970b22a7538f/docs/evidence/claims.md#aws-certification) are recorded explicitly.

## Selected work

| Project | What it demonstrates |
| --- | --- |
| [RAGOps](https://github.com/xmike04/RAG_OPS) | FastAPI, PostgreSQL full-text + pgvector serving, Redis, RRF, async ingestion, and separate offline BM25/MiniLM/SciFact evaluation |
| [SIMLYFE](https://github.com/xmike04/SIMLYFE) | React, deterministic simulation, authenticated LLM integration, Firebase Auth/Firestore, Supabase Edge Functions, Vitest, Vercel |
| [AI/ML portfolio](https://github.com/xmike04/xmike04.github.io) | Next.js, interactive in-browser ML demos, evidence-backed case studies, structured profile data, AI-search discoverability |
| [Canvas Student MCP (npm package)](https://www.npmjs.com/package/canvas-student-mcp) | Published TypeScript MCP integration for read-only Canvas LMS access; source repository is private, and user data remains sensitive |

## Core stack

Python · TypeScript/JavaScript · C++ · SQL · PyTorch · TensorFlow · OpenCV · scikit-learn · React · Next.js · FastAPI · PostgreSQL/pgvector · Firebase · AWS · Google Cloud · Docker · Kubernetes

## Find me

- Portfolio: [michaelmportfolio.org](https://michaelmportfolio.org)
- LinkedIn: [linkedin.com/in/xmike04](https://linkedin.com/in/xmike04)
- Email: [miked24977@gmail.com](mailto:miked24977@gmail.com)

Third-party project evidence: [NASA PACE WAVE](https://pace.oceansciences.org/wave_space_to_ocean.htm) · [UMD Kennedy Center coverage](https://cmns.umd.edu/news-events/news/wave-exhibit-kennedy-center-pace-nasa)
