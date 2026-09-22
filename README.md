<div align="center">

# Yashwant Das

**Lead QA Engineer &amp; Test Automation Architect**

Twelve years in quality engineering. I build systems where LLMs do the fuzzy work —<br>
generation, diagnosis, summarisation — and deterministic checks hold the line.

[![Portfolio](https://img.shields.io/badge/Portfolio-yashwant--das.github.io-181717?logo=github&logoColor=white&style=flat-square)](https://yashwant-das.github.io)
&nbsp;[![LinkedIn](https://img.shields.io/badge/LinkedIn-yashwant--das-0A66C2?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/yashwant-das/)
&nbsp;[![Medium](https://img.shields.io/badge/Medium-Writing-12100E?logo=medium&logoColor=white&style=flat-square)](https://medium.com/@yashwant-das/)

</div>

---

## Start here

### [testing-llm-automation-engine](https://github.com/yashwant-das/testing-llm-automation-engine)

An AI systems engineering workbench for Playwright. It generates TypeScript specs
from a URL and plain-English scenarios — or from a screenshot — using **local**
models through Ollama and LM Studio, with Pydantic-validated structured output.

The part I care about most is the healing loop. When a test breaks, it reads the
DOM, accessibility tree, console and network context, proposes a fix, applies it as
an **AST-level repair** with ts-morph rather than a text patch, then re-runs to
verify the fix actually worked.

Built to be measured, not demoed: JSONL tracing of every model call, benchmarks for
both generation and healing, and **556 unit tests that run with no live LLM and no
browser**.

### [test-playwright-protocol](https://github.com/yashwant-das/test-playwright-protocol)

Smart Playwright Protocol — a six-stage workflow (Select, Understand, Explore, Plan,
Implement, Verify) that keeps AI coding agents reviewable. Markdown task specs driven
from a CLI, verification gates a task cannot close without passing, Page Object
conventions, and optional MCP servers so an agent can explore the browser and manage
its own task list.

---

## What I claim, and where to check it

Every automated decision should be auditable. So should a profile page.

| Claim | Evidence |
|---|---|
| LLM-assisted test generation, running locally | [testing-llm-automation-engine](https://github.com/yashwant-das/testing-llm-automation-engine) — specs from URLs, prose or screenshots via Ollama / LM Studio |
| Explainable, verified test repair | [testing-llm-automation-engine](https://github.com/yashwant-das/testing-llm-automation-engine) — AST repair with ts-morph, then re-run to prove it |
| Measuring AI systems instead of trusting them | [testing-llm-automation-engine](https://github.com/yashwant-das/testing-llm-automation-engine) (tracing, benchmarks, 556 offline tests) · [llm-promptfoo-tests](https://github.com/yashwant-das/llm-promptfoo-tests) (Promptfoo evaluation, no API keys) |
| Keeping AI agents reviewable | [test-playwright-protocol](https://github.com/yashwant-das/test-playwright-protocol) — verification gates, MCP servers |
| Local multimodal tooling | [genai-mlx-playground](https://github.com/yashwant-das/genai-mlx-playground) — MLX Whisper, Moondream, LLaMA 3.2, offline on Apple Silicon |
| Framework architecture, four stacks | [Selenium 4 · Java 21](https://github.com/yashwant-das/web-selenium-java-framework) · [Playwright · Java](https://github.com/yashwant-das/web-playwright-java-framework) · [Selenium · Python](https://github.com/yashwant-das/web-selenium-framework) · [pytest UI + API](https://github.com/yashwant-das/testing-pytest-framework) |
| Load testing with real observability | [performance-locust-framework](https://github.com/yashwant-das/performance-locust-framework) — Locust master/workers, Prometheus, Grafana, alerting |
| OTT playback, DRM and device certification | *No public repo — client work.* Playback, DRM and cross-device certification for streaming platforms including Optus Sport, ALTBalaji, FOX and Mediacorp. |

That last row has no link, and I would rather say so than imply one.

---

## Stack

| | |
|---|---|
| **Automation** | Playwright · Selenium · Appium · WebdriverIO · Cypress · REST Assured · Requests · WireMock · Postman |
| **Languages** | Python · TypeScript · JavaScript · Java |
| **Runners &amp; reporting** | pytest · TestNG · Cucumber · Allure |
| **AI / LLM** | Ollama · LM Studio · MLX · Promptfoo · Pydantic · ts-morph · MCP |
| **Performance** | Locust · JMeter · Prometheus · Grafana |
| **CI/CD &amp; infra** | GitHub Actions · Jenkins · Azure DevOps · Docker |
| **Media &amp; devices** | HLS · MPEG-DASH · Widevine · FairPlay · Conviva · Android · iOS · Fire TV · Roku · Apple TV · Xbox · Smart TV |

---

## How I think about this work

I'm skeptical of QA systems that treat model output as ground truth. My preference is
architectures where AI handles the fuzzy work — pattern recognition, failure
summarization, test suggestion — while deterministic checks enforce the invariants that
actually matter. Every automated decision should be auditable. Claims about AI-assisted
testing should be defensible in production, not just in demos.

I write about this on [Medium](https://medium.com/@yashwant-das/).

---

<div align="center">
<sub><b>Open to Lead QA Engineer, SDET and Test Architect roles</b> — India or remote.<br>
Happy to talk about AI-assisted QA, test architecture, or media quality engineering.</sub>
</div>
