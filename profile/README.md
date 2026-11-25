<div align="center">
  <a href="https://yours.sh">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yours-research/.github/main/profile/assets/hero-dark.png" />
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yours-research/.github/main/profile/assets/hero-light.png" />
      <img alt="Yours Research — Making local inference for everyone." src="https://raw.githubusercontent.com/yours-research/.github/main/profile/assets/hero-light.png" width="100%" />
    </picture>
  </a>

  <p>
    <a href="https://yours.sh"><strong>yours.sh</strong></a>
    &nbsp;&middot;&nbsp;
    <a href="https://huggingface.co/yours-research"><strong>Hugging Face</strong></a>
    &nbsp;&middot;&nbsp;
    <a href="https://x.com/yoursdotsh"><strong>X (@yoursdotsh)</strong></a>
  </p>
</div>

**Yours Research** is an independent lab building hardware-co-designed small language models, browser-native WebGPU inference runtimes, and open local SDKs so capable AI runs privately on the device in front of you.

## Flagship Product

| Repository | Description | Stack |
| :--- | :--- | :--- |
| [`yours-browser-extension`](https://github.com/yours-research/yours-browser-extension) | Offline-first Chromium MV3 AI side panel powered by a custom Rust WASM + native WGSL WebGPU compute engine (`q4f16`, INT8 KV cache, 128K context). | `TypeScript` &middot; `Rust` &middot; `WGSL` |

## Modular SDK Ecosystem (`Apache-2.0` &middot; `@yours/*`)

| Repository | Package | Focus |
| :--- | :--- | :--- |
| [`yours-tools`](https://github.com/yours-research/yours-tools) | `@yours/tools` | Dual Chromium MV3 + web-demo assistant tools SDK: canonical schemas, semantic AOM extraction, local PDF parsing, and QuickJS-WASM sandbox. |
| [`yours-harness`](https://github.com/yours-research/yours-harness) | `@yours/harness` | Runtime-agnostic local LLM chat & agent harness: KV-cache-preserving compaction, prefix slot scheduling, OPFS/IDB persistence, and tool streaming state machine. |
| [`yours-memory`](https://github.com/yours-research/yours-memory) | `@yours/memory` | Hybrid local AI memory engine for Chrome MV3: Dedicated Worker OPFS SQLite-WASM FTS5 + quantized HNSW vector search, salience decay, and privacy controls. |
| [`yours-models`](https://github.com/yours-research/yours-models) | `@yours/models` | Verified browser model delivery & WebGPU hardware prober: parallel `Range`/HTTP3 OPFS downloader, Ed25519 signed manifests, and streaming SHA-256 verification. |
| [`yours-guard`](https://github.com/yours-research/yours-guard) | `@yours/guard` | Zero-cloud indirect prompt injection (IDPI) defense & capability policy engine: DOM sanitization, spotlighting delimiters, taint tracking, and Lethal Trifecta gate. |
| [`yours-voice`](https://github.com/yours-research/yours-voice) | `@yours/voice` | 100% local browser voice pipeline: Silero VAD WASM, streaming Whisper/Moonshine WebGPU STT, and Kokoro TTS with instant barge-in cancellation. |
| [`yours-evals`](https://github.com/yours-research/yours-evals) | `@yours/evals` | End-to-end local assistant benchmark and regression suite covering tools, compaction, memory recall, IDPI robustness, and voice latency. |

<br />

<div align="center">
  <sub><code>yours / research</code> &nbsp;&middot;&nbsp; Making local inference for everyone.</sub>
</div>
