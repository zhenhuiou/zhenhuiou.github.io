---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<h2><b>Welcome to Zhenhui’s Homepage!</b></h2>

I am Zhenhui Ou, a second-year PhD student at Arizona State University (ASU). Previously, I received my Bachelor's degree in Automation at Fuzhou University (FZU) and Maynooth University (MU). I am very fortunately advised by and maintain closely connected with Prof. [Huan Liu](https://search.asu.edu/profile/255975), Prof. [Lingyao Li](https://www.lingyaoli.com/), Prof. [Wenlin Liu](https://wenxiliu.github.io/), [Dawei Li](https://david-li0406.github.io/) and [Zhen Tan](https://zhen-tan-dmml.github.io/).

My work centers on **large-scale, domain-adapted LLMs** and **multimodal, tool-augmented agents** that ground reasoning in perception, simulation, and structured knowledge to deliver **reliable, verifiable decision support** for safety-critical, unstructured environments. I further translate these capabilities to **language-conditioned robotics**. Linking perception, whole-body control, and dexterous manipulation, humanoid/mobile platforms can execute LLM-generated plans with **closed-loop reliability**.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2025</div><img src='images/CIKM25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Building Safer Sites: A Large-Scale Multi-Level Dataset for Construction Safety Research](https://dl.acm.org/doi/pdf/10.1145/3746252.3761652)

**Zhenhui Ou**, Dawei Li, Zhen Tan, Wenlin Li, Huan Liu, Siyuan Song.
- This paper introduces CSDataset, a large-scale multi-level OSHA construction safety benchmark that links incidents–inspections–violations (2013–2022) with both structured attributes and narrative text to enable ML/LLM benchmarking and cross-level analyses such as injury severity prediction and inspection–incident causal insights 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/EMNLP25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLMs as World Models: Data-Driven and Human-Centered Pre-Event Simulation for Disaster Impact Assessment](https://aclanthology.org/2025.emnlp-main.153.pdf)

Lingyao Li, Dawei Li, **Zhenhui Ou**, Xiaoran Xu, Jingxiao Liu, Zihui Ma, Runlong Yu, Min Deng.
- This paper proposes an LLM-as-world-model framework that fuses multimodal pre-event context to simulate human-perceived earthquake impacts at zip scales, achieving strong agreement with USGS “Did You Feel It?” reports and showing gains from RAG/ICL and visual inputs. 
</div>
</div>

# 🎖 Honors and Awards
- *2026.01* ASU University Graduate Fellowship.
- *2025.11* ASU Graduate College Travel Award.
- *2024.09* ASU Fulton Fellowship. ASU Ira A. Fulton Schools of Engineering PhD Fellowships.
- *2023.12* Innovation Scholarship (One of the highest undergraduate awards).
- *2022.08* China University Intelligent Robot Competition First Prize (Simulated spider plot robot).
- *2021.05* First Prize Scholarship of MIEC (Top 1% students in FZU).

# 📖 Educations
- *2024.09 - Present*, Arizona State University, Ph.D. in Artificial Intelligence & Robotics 
- *2020.09 - 2024.06*, Maynooth University, BS in Robotics and Intelligent Devices (**First-Class Honours**).
- *2020.09 - 2024.06*, Fuzhou University, BE in Automation.

# 💻 Experience
- Arizona State University, *2024.09 - 2026.01*.
  - Research Assistant.
  - Worked on LLM-enhanced construction safety analytics by building a large-scale incidents–inspections–violations dataset, developing hybrid ML+LLM risk modeling with interpretable explanations, designing an LLM-as-a-Judge evaluation pipeline, and proposing an evidence-driven multi-agent framework for grounded safety reasoning and uncertainty-aware auditing. 
- Fuzhou University, *2022.07 - 2024.05*.
  - Research Intern.
  - Worked with Prof. [Wenlin Liu](https://wenxiliu.github.io/) and Prof. [Yutao Chen](https://dqxy.fzu.edu.cn/dqgcxyxin/info/1041/4136.htm) on safe reinforcement-learning-based autonomous robot navigation in dynamic, unknown environments, and on Simulink/Adams virtual prototyping for CPG-driven quadruped gait and motion control.

# 💬 Service
- Serve as a reviewer for CVPR 2024, CIKM 2025 and CRC 2026.
- Teaching Assistant: FZU & MU CS427 Autonomous Mobile Robotics, Fall 2023.
- Teaching Assistant: FZU & MU EE311 Control System Design, Spring 2023.
- Teaching Assistant: FZU & MU EE204 Analog Electronics, Fall 2022.
