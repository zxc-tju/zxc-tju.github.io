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

# 💬 About Me
I am currently a Postdoctoral Researcher at the College of Transportation Engineering, Tongji University. I received my Ph.D. degree in Transportation Engineering from Tongji University in May 2025, with the thesis titled "Sociality-Aware Interactive Motion Planning for Autonomous Driving". 

From Nov. 2022 to Oct. 2023, I was a visiting scholar at the Technical University of Dresden (TU Dresden), Germany, under the supervision of Prof. [Meng Wang](https://tu-dresden.de/bu/verkehr/vis/vpa/die-professur/head-of-chair).

I have published over 20 papers in top journals and conferences such as *IEEE T-ITS*, *AA&P*, and *Scientific Data*. I won the Champion of the 2022 CommonRoad Motion Planning Competition for Autonomous Vehicles and the Silver Medal at the 2023 International Exhibition of Inventions of Geneva. I was awarded the IEEE ITSS Initiative Project. Since 2024, I have served as a workshop chair, organizing and hosting the "Human-Machine Interaction" workshop at the IEEE ITSC International Conference.

## Research Interests
- Interactive Motion Planning
- Modeling Social Driving Behaviors
- Human-Machine Interaction for Autonomous Driving
<br>

I am open to any interest on my work or collaborative research topics (zhaoxc@tongji.edu.cn).


# 🔥 News
- *2025.11* 🔥 &nbsp;I organized and hosted a workshop on "From Interface to Intelligence: HMI 2.0 for Socially Compliant Autonomous Vehicles" at IEEE ITSC 2025 in Australia. [[workshop site](https://sites.google.com/view/workshop-itsc-2025/%E9%A6%96%E9%A1%B5)]
- *2025.07* 🔥 &nbsp;Our work, "InterHub: A Naturalistic Trajectory Dataset with Dense Interaction for Autonomous Driving", has been published in _Scientific Data_. [[paper]](https://www.nature.com/articles/s41597-025-05344-7)[[dataset]](https://figshare.com/articles/dataset/_b_InterHub_A_Naturalistic_Trajectory_Dataset_with_Dense_Interaction_for_Autonomous_Driving_b_/27899754)[[code]](https://github.com/zxc-tju/InterHub).
- *2025.05* 🔥 &nbsp; I’ve defended my Ph.D. thesis on “Sociality-Aware Interactive Motion Planning for Autonomous Driving” at Tongji University. 
- *2024.12*  &nbsp;Excited to announce that our work, "InterHub: A Naturalistic Trajectory Dataset with Dense Interaction for Autonomous Driving", is now available! Check out the [[preprint paper]](https://arxiv.org/abs/2411.18302), [[dataset]](https://figshare.com/articles/dataset/_b_InterHub_A_Naturalistic_Trajectory_Dataset_with_Dense_Interaction_for_Autonomous_Driving_b_/27899754), and [[code]](https://github.com/zxc-tju/InterHub).
- *2024.07*  &nbsp;I will be holding a workshop "Advanced Modeling, Evaluation, and Simulation of Interactions in Mixed Traffic" at ITSC 2024 during September 24- 27, 2024 in Edmonton, Canada.[[workshop site](https://sites.google.com/view/workshop-itsc-2024)]
- *2024.07*  &nbsp;Our work "Towards Interactive Autonomous Vehicle Testing: Vehicle-Under-Test-Centered Traffic Simulation" has been accepted by IEEE ITSC 2024. My colleague [Yiru Liu](https://www.linkedin.com/in/yiru-liu-b407312b9/) will be presenting this work at ITSC 2024 in Edmonton, Canada.[[paper](https://arxiv.org/html/2406.02860v2)] [[code](https://github.com/YNYSNL/VCDI)]
- *2024.04*  &nbsp;Our work "Measuring Sociality in Driving Interaction" has been published on IEEE Transactions on Intelligent Transportation Systems. [[paper](https://ieeexplore.ieee.org/document/10499856)]
- *2024.04*  &nbsp;Our proposal "Evidence-Based Communication Channel for Autonomous Driving Technology" has been officially funded by the 2024 IEEE ITSS New Initiatives Program.
- *2024.01*  &nbsp;We present our poster on "Modeling Social Interaction Behaviors and Measuring Driving Sociality in Strong Interactive Scenarios" at 2024 Transportation Research Board Annual Meeting.
- *2023.06*  &nbsp;We present our paper on "Towards Active Motion Planning in Interactive Driving Scenarios: A Generic Utility Term of Interaction Activeness" at 2023 IEEE IV. [[paper](https://ieeexplore.ieee.org/abstract/document/10186564)]
- *2023.05*  &nbsp;We are awarded the golden prize on 2023 International Exhibition of Inventions of Geneva. [[link](https://tops.tongji.edu.cn/info/1002/1661.htm)]
- *2022.06*  &nbsp;Our team won the championship of the Commonroad Motion Planning Competition for Autonomous Vehicles! [[link](https://commonroad.in.tum.de/competition/2022/announcement)] [[talk](https://www.youtube.com/watch?v=jNOmQOFEscs)]

# 🎓 Education
- *2025.09 - Present*, Postdoctoral Researcher in Transportation Engineering, Tongji University.
- *2022.11 - 2023.11*, Visiting Scholar, TU Dresden.
- *2020.09 - 2025.06*, Ph.D. in Transportation Engineering, Tongji University.
- *2017.09 - 2020.06*, M.S. in Vehicle Engineering, Jiangsu University - Tsinghua University (Joint).
- *2013.09 - 2017.06*, B.S. in Vehicle Engineering, Jiangsu University.

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Scientific Data 2025</div><img src='images/roadmap_Interhub.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InterHub: A Naturalistic Trajectory Dataset with Dense Interaction for Autonomous Driving](https://www.nature.com/articles/s41597-025-05344-7)

[Xiyan Jiang](https://tops.tongji.edu.cn/info/1161/2143.htm), **Xiaocong Zhao\***, [Yiru Liu](https://tops.tongji.edu.cn/info/1131/1810.htm), [Zirui Li](https://lzrbit.github.io/), [Peng Hang](https://tops.tongji.edu.cn/info/1031/1383.htm), Lu Xiong, and [Jian Sun](https://tops.tongji.edu.cn/info/1031/1187.htm)

[**Project**](https://github.com/zxc-tju/InterHub) [![](https://img.shields.io/github/stars/zxc-tju/InterHub?style=social&label=Code%20Stars)](https://github.com/zxc-tju/InterHub)

- A naturalistic driving dataset with dense interactions is extracted from multiple widely adopted public driving datasets, being unified, analyzed, and categorized to provide a user-friendly data foundation.
- A quantitative-yet-readable definition of the driving interaction using the formal method is proposed along with an open access toolkit.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ITSC 2024</div><img src='images/ITSC2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Interactive Autonomous Vehicle Testing: Vehicle-Under-Test-Centered Traffic Simulation](https://arxiv.org/html/2406.02860v1)

[Yiru Liu](https://ynysnl.github.io/), **Xiaocong Zhao\***, [Jian Sun](https://tops.tongji.edu.cn/info/1031/1187.htm)

- This study introduces an Vehicle-under-test-Centered environmental Dynamics Inference (VCDI) model for realistic, interactive, and diverse background traffic simulation.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-ITS 2024</div><img src='images/tits2024-hd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Measuring Sociality in Driving Interaction](https://ieeexplore.ieee.org/document/10499856)

**Xiaocong Zhao**, [Jian Sun\*](https://tops.tongji.edu.cn/info/1031/1187.htm), [Meng Wang](https://tu-dresden.de/bu/verkehr/vis/vpa/die-professur/head-of-chair)

- We introduce a novel framework designed to analyze social behaviors through driving trajectories.
- By understanding and quantifying social patterns in natural driving interactions, we demonstrate the potential to enhance autonomous driving technologies by incorporating human strategies in expressing sociality.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-ITS 2024</div><img src='images/sociality_probe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Sociality probe: Game-theoretic inverse reinforcement learning for modeling and quantifying social patterns in driving interaction](https://ieeexplore.ieee.org/abstract/document/10693867)

Yiru Liu, **Xiaocong Zhao**, Ye Tian, et al.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE IV 2023</div><img src='images/IV2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Active Motion Planning in Interactive Driving Scenarios: A Generic Utility Term of Interaction Activeness](https://ieeexplore.ieee.org/abstract/document/10186564)

 **Xiaocong Zhao**,  [Meng Wang](https://tu-dresden.de/bu/verkehr/vis/vpa/die-professur/head-of-chair), Shiyu Fang, [Jian Sun\*](https://tops.tongji.edu.cn/info/1031/1187.htm)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TR-C 2022</div><img src='images/reasoning_graph.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reasoning Graph: A Situation-aware framework for cooperating unprotected turns under mixed connected and autonomous traffic environments](https://doi.org/10.1016/j.trc.2022.103815)

Donghao Zhou, Zian Ma, **Xiaocong Zhao**, et al.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ITSC 2021</div><img src='images/ITSC2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Yield or rush? Social-preference-aware driving interaction modeling using game-theoretic framework](https://ieeexplore.ieee.org/abstract/document/9564702)

**Xiaocong Zhao**,  [Ye Tian](https://tops.tongji.edu.cn/info/1031/1185.htm), [Jian Sun\*](https://tops.tongji.edu.cn/info/1031/1187.htm)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AA&P 2020</div><img src='images/AAP2020.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[How do drivers respond to driving risk during car-following? Risk-response driver model and its application in human-like longitudinal control](https://www.sciencedirect.com/science/article/pii/S0001457520316031)

**Xiaocong Zhao**, Ren He, Jianqiang Wang\*

</div>
</div>



# 🎖 Honors and Awards
- 2023 Silver Medal, International Exhibition of Inventions of Geneva.
- 2022 Champion, CommonRoad Motion Planning Competition for Autonomous Vehicles.
- 2022-2023 Graduate Student Fellowship of China Scholarship Council (CSC).
- 2021 Outstanding Graduate Student Scholarship of Tongji University.
- 2017 Grand Prize, China-Japan-Korea Innovation Engineering Competition.
- 2019, 2018, 2015 National Scholarship for College Students (Top 1%).

# Services
## Conference Organization
- **Host**, Youth Academic Frontier Forum, CSAE Xingzhi College (2025.12). Topic: Development and Application of Human-Machine Interaction Technology for Intelligent Driving.
- **Organizer & Host**, Workshop on "From Interface to Intelligence: HMI 2.0 for Socially Compliant Autonomous Vehicles", IEEE ITSC 2025 (Australia).
- **Organizer**, Workshop on "Advanced Modeling, Evaluation, and Simulation of Interactions in Mixed Traffic", IEEE ITSC 2024 (Canada).

## Guest Editor
- *Actuators (Special Issue)*, "Embodied Intelligence and Actuator Co-Design for Autonomous Vehicles", 2025.

## Project Leader
- Working group leader of 2024 IEEE ITSS New Initiatives Program “Evidence-Based Communication Channel for Autonomous Driving Technology”.

## Reviewer
- IEEE Transactions on Intelligent Transportation Systems
- Transportation Research Part C
- Computer-Aided Civil and Infrastructure Engineering
- IET Intelligent Transport Systems
- Automotive Innovation
- etc.

## Membership
- IEEE Member
- IEEE Intelligent Transportation Systems Society Member
