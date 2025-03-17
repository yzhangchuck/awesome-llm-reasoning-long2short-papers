# 🚀 Awesome Long2Short Papers

A curated list of papers about making LLM reasoning more efficient (shorter/faster/better).

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![arXiv](https://img.shields.io/badge/arXiv-Papers-b31b1b.svg)](https://arxiv.org)
[![Update](https://img.shields.io/badge/Update-Daily-green.svg)](https://github.com/your-username/awesome-long2short-papers)

## 📰 News

🎉 **Latest Update**: Our paper collection is continuously updated. Feel free to contribute!

## 📝 Citation

If you find this resource helpful, please cite the relevant papers:

```bibtex
@misc{awesome-long2short-papers,
  title={Awesome Long2Short Papers},
  author={Community Contributors},
  year={2024},
  publisher={GitHub},
  howpublished={\url{https://github.com/yzhangchuck/awesome-llm-reasoning-long2short-papers}}
}
```

## 📚 Table of Contents

- [🔍 Analysis and Understanding](#analysis)
- [🤔 Reasoning Scaling](#reasoning_scaling)
- [⚡ Inference Intervention](#inference)
- [🧠 Latent Reasoning](#latent)
- [📚 Supervised Fine-tuning](#sft)
- [🎛️ Steering Vector](#steering)
- [🎯 Reinforcement Learning Approaches](#rl)
- [🌟 General Papers](#general)


---


## 🔍 Analysis and Understanding <a id="analysis"></a>

Deep dives into LLM reasoning

| Title | Year | Venue | Paper | Code |
|-------|------|-------|-------|------|
| **How Well do LLMs Compress Their Own Chain-of-Thought? A Token Complexity Approach** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2503.01141) | [[Code]](https://github.com/Compressed-CoT/compressed-cot) |
| **Towards Thinking-Optimal Scaling of Test-Time Compute for LLM Reasoning** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.18080) | - |
| **Do NOT Think That Much for 2+3=? On the Overthinking of o1-Like LLMs** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2412.21187) | - |



## 🤔 Reasoning Scaling <a id="reasoning_scaling"></a>

Scaling up reasoning

| Title | Year | Venue | Paper | Code |
|-------|------|-------|-------|------|
| **Beyond Human Data  Scaling Self Training for Problem Solving with Language Models** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/beyondhumandatascalingselftrainingforproblemsolvingwithlanguagemodels) | - |
| **Let’s Verify Step by Step** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/let’sverifystepbystep) | - |
| **REFT  Reasoning with REinforced Fine Tuning** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/reftreasoningwithreinforcedfinetuning) | - |
| **ReST MCTS∗  LLM Self Training via Process Reward Guided Tree Search** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/restmcts∗llmselftrainingviaprocessrewardguidedtreesearch) | - |
| **Recursive Introspection  Teaching Language Model Agents How to Self Improve** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/recursiveintrospectionteachinglanguagemodelagentshowtoselfimprove) | - |
| **Scaling LLM Test Time Compute Optimally can be More Effective than Scaling Model Parameters** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/scalingllmtesttimecomputeoptimallycanbemoreeffectivethanscalingmodelparameters) | - |
| **Test Time Preference Optimization  On the Fly Alignment via Iterative Textual Feedback** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/testtimepreferenceoptimizationontheflyalignmentviaiterativetextualfeedback) | - |



## ⚡ Inference Intervention <a id="inference"></a>

Interventions during model inference process

| Title | Year | Venue | Paper | Code |
|-------|------|-------|-------|------|
| **When More is Less- Understanding Chain-of-Thought Length in LLMs** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.07266) | - |



## 🧠 Latent Reasoning <a id="latent"></a>

Reasoning in latent spaces

| Title | Year | Venue | Paper | Code |
|-------|------|-------|-------|------|
| **LightThinker- Thinking Step-by-Step Compression** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.15589) | - |
| **Scaling up Test-Time Compute with Latent Reasoning- A Recurrent Depth Approach** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.05171) | [[Code]](https://github.com/seal-rg/recurrent-pretraining) |
| **Token Assorted- Mixing Latent and Text Tokens for Improved Language Model Reasoning** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.03275) | - |
| **Compressed Chain of Thought- Efficient Reasoning through Dense Representations** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2412.13171) | - |
| **Quiet-STaR- Language Models Can Teach Themselves to Think Before Speaking** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2403.09629) | - |
| **Training Large Language Models to Reason in a Continuous Latent Space** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2412.06769) | - |



## 📚 Supervised Fine-tuning <a id="sft"></a>

Direct optimization for efficiency

| Title | Year | Venue | Paper | Code |
|-------|------|-------|-------|------|
| **Self-Training Elicits Concise Reasoning in Large Language Models** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.20122) | [[Code]](https://github.com/TergelMunkhbat/concise-reasoning) |
| **TokenSkip- Controllable Chain-of-Thought Compression in LLMs** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.12067) | [[Code]](https://github.com/hemingkx/TokenSkip) |
| **s1- Simple test-time scaling** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2501.19393) | [[Code]](https://github.com/simplescaling/s1) |



## 🎛️ Steering Vector <a id="steering"></a>

Steering model behavior through vector manipulation

| Title | Year | Venue | Paper | Code |
|-------|------|-------|-------|------|
| **CoT-Valve- Length-Compressible Chain-of-Thought Tuning** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.09601) | - |



## 🎯 Reinforcement Learning Approaches <a id="rl"></a>

Training models to reason efficiently

| Title | Year | Venue | Paper | Code |
|-------|------|-------|-------|------|
| **Kimi k1.5: Scaling Reinforcement Learning with LLMs** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2501.12599) | - |
| **L1- Controlling How Long A Reasoning Model Thinks With Reinforcement Learning** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2503.04697) | [[Code]](https://github.com/cmu-l3/l1) |
| **O1-Pruner- Length-Harmonizing Fine-Tuning for O1-Like Reasoning Pruning** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2501.12570) | [[Code]](https://github.com/StarDewXXX/O1-Pruner) |
| **Training Language Models to Reason Efficiently** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.04463) | [[Code]](https://github.com/Zanette-Labs/efficient-reasoning) |



## 🌟 General Papers <a id="general"></a>

Latest advances in efficient reasoning

| Title | Year | Venue | Paper | Code |
|-------|------|-------|-------|------|
| **Inner Thinking Transformer- Leveraging Dynamic Depth Scaling to Foster Adaptive Internal Thinking** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.13842) | - |
| **Learning to Reason from Feedback at Test-Time** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.15771) | [[Code]](https://github.com/LaVi-Lab/FTTT) |
| **S\*: Test Time Scaling for Code Generation** | 2025 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2502.14382) | [[Code]](https://github.com/NovaSky-AI/SkyThought) |
| **Efficiently Serving LLM Reasoning Programs with Certaindex** | 2024 | arXiv preprint | [[Paper]](https://arxiv.org/abs/2412.20993) | - |


## 🤝 Contributing

We welcome contributions! Please feel free to submit a pull request to add more papers or improve the existing content.

### Contribution Guidelines

1. Please ensure the paper is related to efficient LLM reasoning
2. Follow the existing format
3. Add a brief description if possible
4. Include links to paper and code (if available)


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yzhangchuck/awesome-llm-reasoning-long2short-papers&type=Date)](https://star-history.com/#yzhangchuck/awesome-llm-reasoning-long2short-papers&Date)