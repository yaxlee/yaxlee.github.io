---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I'm a Ph.D. candidate in Mechanical Engineering at [Stevens Institute of Technology](https://www.stevens.edu/), advised by [Brendan Englot](https://scholar.google.com/citations?user=Nd6tX_kAAAAJ&hl=en) in the [Robust Field Autonomy Lab](https://robustfieldautonomylab.github.io/). Before Stevens, I received my Master's degree from [NYU](https://www.nyu.edu/), advised by [Chen Feng](https://scholar.google.com/citations?user=YeG8ZM0AAAAJ&hl=en) in the [AI4CE Lab](https://ai4ce.github.io/), and my Bachelor's degree from the Qiushi Honors College at [Tianjin University](https://en.tju.edu.cn/).

I'm interested in robot localization and perception. Currently, I'm working on multi-modal SLAM, multi-sensor fusion and 3D perception for robots. I also have extensive deployment experience on ground, aerial, and surface vehicles with cameras, IMUs, LiDAR and GNSS. Here is my [CV](YaxuanLi.pdf).

# News
- *2026.06* Joined the **General Motors Autonomous Robotics Center** as a Ph.D. intern, working on visual localization and 3D LiDAR perception for autonomous mobile robots.
- *2026.06* **SGM-SLAM**, a data-efficient distributed SLAM system based on scene graph matching, is on [arXiv](https://arxiv.org/abs/2606.16881).
- *2026.05* **Above and Below**, a multi-robot SLAM system across surface and underwater domains, is on [arXiv](https://arxiv.org/abs/2605.09811).
- *2025.08* Our **IROS 2025** paper **CVD-SfM** is on [arXiv](https://arxiv.org/abs/2508.01936), with [code and two new multi-altitude datasets](https://github.com/RobustFieldAutonomyLab/CVD-SfM).

# Publications

<div class='paper-box'><div class='paper-box-image'><div><img src='papers/dgvi-slam.png' alt="DGVI-SLAM system overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DGVI-SLAM: DEM-Aided Visual–Inertial SLAM with Bounded GNSS Recovery** <span class="pub-venue">ICRA 2027 (under review)</span>

**Yaxuan Li**, [Co-authors]

Globally referenced localization that fuses camera, IMU, GNSS and a digital elevation model for urban environments with varying elevation and degraded GNSS. DEM integration reduces median position RMSE by 30% across six urban sequences.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='papers/sgm-slam.png' alt="SGM-SLAM multi-layer scene graph" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SGM-SLAM: Scene Graph Matching for Data-Efficient Distributed SLAM** <span class="pub-venue">arXiv</span>

Yewei Huang, Tixiao Shan, Abhinav Rajvanshi, Niluthpol Chowdhury Mithun, **Yaxuan Li**, [Brendan Englot](https://scholar.google.com/citations?user=Nd6tX_kAAAAJ&hl=en), Han-Pang Chiu

[arXiv](https://arxiv.org/abs/2606.16881)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='papers/above.png' alt="Above and Below system flow" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Above and Below: Heterogeneous Multi-Robot SLAM Across Surface and Underwater Domains** <span class="pub-venue">arXiv</span>

John McConnell, Armon Shariati, Paul Szenher, **Yaxuan Li**

[arXiv](https://arxiv.org/abs/2605.09811)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='papers/cvd-sfm.png' alt="CVD-SfM pipeline" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CVD-SfM: A Cross-View Deep Front-end Structure-from-Motion System for Sparse Localization in Multi-Altitude Scenes** <span class="pub-venue">IROS 2025</span>

**Yaxuan Li**, Yewei Huang, Bijay Gaudel, Hamidreza Jafarnejadsani, [Brendan Englot](https://scholar.google.com/citations?user=Nd6tX_kAAAAJ&hl=en)

[arXiv](https://arxiv.org/abs/2508.01936) \| [Code & Data](https://github.com/RobustFieldAutonomyLab/CVD-SfM)
</div>
</div>

# Experience
- *2026.06 – 2026.08* **General Motors, Autonomous Robotics Center**, Warren, MI. Autonomous Robot Software Engineer Intern (Ph.D.)
  - *Visual-assisted localization in dynamic plant environments* (sole developer): built visual global localization on top of LiDAR-inertial SLAM (Cartographer) for initialization and re-localization, extending NVIDIA cuVGL on Jetson AGX Orin with SuperPoint/LightGlue and 3D-map PnP. Achieved 3 cm accuracy at 0.3 s/frame on the deployed robot.
  - *3D LiDAR localization*: deployed and benchmarked FAST-LIO on a 128-channel Ouster LiDAR for next-generation AMRs, with keyframe-based submaps registered by GICP.
  - *3D LiDAR object detection and segmentation* (sole developer): exported mmdetection3d models to TensorRT on Jetson AGX Orin; built a real-world plant dataset in CVAT and synthetic data with dynamic pedestrians and obstacles in Isaac Sim.
- *2023.09 – present* **Robust Field Autonomy Lab, Stevens Institute of Technology**, Hoboken, NJ. Ph.D. research with Brendan Englot on multi-sensor SLAM, geo-referenced localization and multi-robot mapping.
- *2022.09 – 2023.05* **AI4CE Lab, New York University**, New York, NY. Worked with Chen Feng on Dynamic-Aware SuperPoint, a feature extractor that classifies interest points as static, quasi-static or dynamic for robust visual SLAM in dynamic scenes.
- *2021.03 – 2021.06* **Sysware Technology Co., Ltd.**, Beijing, China. Software Development Engineer Intern.

# Education
- *2023 – 2027 (expected)* Ph.D. in Mechanical Engineering, Stevens Institute of Technology. Provost Doctoral Fellowship (2023–2024).
- *2021 – 2023* M.S. in Mechatronics and Robotics, New York University.
- *2016 – 2020* B.S. in Machinery Design, Manufacture and Its Automation, Qiushi Honors College, Tianjin University.

# Skills
- **Programming:** C++, Python, PyTorch, TensorRT, ROS/ROS 2, Ceres, GTSAM, g2o, OpenCV, OpenGL
- **Localization:** multi-sensor odometry and SLAM, visual-inertial navigation (VINS)
- **3D vision:** 3D reconstruction, SfM, NeRF, 3DGS, 3D object detection, semantic segmentation
- **Sensors:** calibration and fusion of camera, LiDAR, IMU, GNSS (RTK, PPK)
- **Platforms:** UGV, UAV, USV, NVIDIA Jetson, Isaac Sim, CUDA, Gazebo, Docker, Slurm, AWS
