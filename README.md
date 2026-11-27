I'm a Ph.D. student at **USTC**. My research spans **data management and information retrieval**, as well as **LLM post-training and agents**. Open to job opportunities worldwide.

---

## Research & Open Source

### Vector Search

- **[Faiss](https://github.com/facebookresearch/faiss)** — Implemented GPU IVF `add_preassigned` support via `add_core` for custom partitioning and routing ([#5372](https://github.com/facebookresearch/faiss/pull/5372)), and fixed a cuVS-backed IVFPQ validation issue ([#4241](https://github.com/facebookresearch/faiss/pull/4241)).
- **[ROTLEX](https://github.com/weiwch/rotlex)** · `KDD 2025` · *First author* — Robust tree-based learned vector indexing with query-aware repartitioning.
- Other contributions: [Qdrant](https://github.com/qdrant/qdrant/pull/5608) · [NGT](https://github.com/NGT-labs/NGT/pull/182)

### Databases & AI4DB

- **[PilotScope](https://github.com/alibaba/pilotscope)** · `VLDB 2024` · **Core contributor** ([56 commits](https://github.com/alibaba/pilotscope/commits?author=weiwch))  
  Contributed substantially to the design, development, and refactoring of the AI4DB middleware, bridging machine learning algorithms and database systems.
  - [Database control interfaces](https://github.com/alibaba/pilotscope/commit/e7b1eb5553a408613f8cf40d39db4326655e3d66) and Python APIs for database interaction.
  - [`pg_hint_plan`](https://github.com/ossc-db/pg_hint_plan) [integration](https://github.com/alibaba/pilotscope/commit/bacb018ca74133326135271f6165cda3a4c7647e) and [query-plan control](https://github.com/alibaba/pilotscope/commit/06f7c1ac62c5a2fbd5962442903669dc2d7593f7).
  - [System architecture refactoring](https://github.com/alibaba/pilotscope/commit/da56313691b6b335f3e670b25fd1b7ac852a9658), experiment infrastructure, and AI4DB algorithm integration.
- Other contributions: [HypoPG](https://github.com/HypoPG/hypopg/pull/81)

### Generative Search & Recommendation

- **[LGMPS](https://github.com/weiwch/LGMPS)** · `WSDM 2027` · *First author* — Linear-time generative personalized search combining session-local attention with Gated DeltaNet for long-range user behavior modeling.

### LLMs & Agents

- **[AREX-2](https://github.com/VectorSpaceLab/AREX-2)** · *Co-first author* — LLM post-training through long-horizon reflective trajectories for self-improving agents and test-time scaling.
- **[AREX-Skill](https://github.com/VectorSpaceLab/AREX-Skill)** · *Co-first author* — Distilling repository knowledge into executable skills for autonomous research agents. Developed the [Algorithmic Problem-Solving Skill](https://github.com/VectorSpaceLab/AREX-Skill/tree/main/skills/task-oriented/FrontierCS/algorithmic-problem-solving) ([#21](https://github.com/VectorSpaceLab/AREX-Skill/pull/21)).
- Other contributions: [Frontier-CS #162](https://github.com/FrontierCS/Frontier-CS/pull/162)

### Tech Stack

`C/C++` `Python` `PyTorch` `PostgreSQL` `Linux`
