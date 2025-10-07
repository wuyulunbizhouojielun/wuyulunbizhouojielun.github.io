---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in College of Optical Science and Engineering(COSE), Zhejiang University  2021-2025

Work experience
======
* 7/2025 - Present: Research on Reasoning LLM/MLLM Quantization
  * Westlake University
  * Duties includes:
    * Apply mainstream quantization methods on reasoning models
  * Supervisor: Prof. Huan Wang

* 10/2024 - 6/2025: Research on lightweight Event-based gaze-tracking Algorithm
  * Zhejiang University
  * Duties includes:
    * Explored the usage of mainstream event cameras and mastered the operation of related SDKs
    * Ran experiments on various mainstream eye tracking and gaze estimation algorithms
    * Optimized the existing event-driven eye-tracking methods based on lightweight neural networks
    * Learned fundamental knowledge in machine learning and computer vision
  * Supervisor: Prof. Kaiwei Wang

* 10/2023 - 08/2024: Localization and tracking of wheel-legged robots based on multi-sensor fusion
  * Zhejiang University
  * Duties included:
    * Implemented data collection and stream processing on Livox lidar and industrial cameras
    * Conducted the procedure of dataset making, training and employment for yolov5 and yolov8 models
    * Learned the basic usage of inference acceleration libraries such as TensorRT
    * Improved current real-time fusion localization methods using RGB images and lidar point cloud
    * Cultivated engineering mindset and teamwork skills

* 10/2022 - 06/2023: Research on the spatiotemporal distribution characteristics of ice edge phytoplankton based on spaceborne LiDAR CALIOP
  * Zhejiang University
  * Duties included:
    * Implemented satellite data processing algorithm with MATLAB on data from CALIOP and Sentinel-2
    * Optimize existing methods for small-scale surface types classification
    * Received an excellent rating in the final defense
  * Supervisor: Prof. Dong Liu
  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
