# About

Hi! My name is Frank, I am currently a Computer Science MS student at Northwestern University at the [Design Automation of Intelligent Systems Lab](http://zhulab.eecs.northwestern.edu/index.html) advised by Prof. [Qi Zhu](http://users.eecs.northwestern.edu/~qzhu/). I also work closely with Prof. [Chao Huang](https://chaohuang2018.github.io/) at University of Southampton. I am also worked as a Robotics Learning Intern at the [Stanford Vision and Learning Lab](https://svl.stanford.edu/) advised by Prof. [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li). 

I received my Bachelor's Degree with <i>summa cum laude</i> in Computer Science and Mathematics in 2024, also from Northwestern University. I had the privilege of collaborating with Professor [Florian Willomitzer](https://www.optics.arizona.edu/person/florian-willomitzer) at the [3DIM Lab](https://3dim.northwestern.edu/). 

I have a broad interest in robotic learning and control. I’m fascinated by the challenge of building autonomous robots that navigate complex environments and perform long-horizon tasks efficiently and safely. I am researching on equipping robots with safe learning and runtime decision-making capabilities within uncertain environments subject to disturbances or observation delays. This interest extends from common applications like self-driving vehicles to humanoid robotics. Looking ahead, I aim to design state-of-the-art learning methods that effectively assist humans in complex tasks, while prioritizing safety alongside performance.

Within robotic learning and control, I am particularly interested in:

***Data-Driven Control in Uncertainty***: developing safe reinforcement learning and model predictive control strategies that can handle uncertainties and observation delays in dynamic environments.

***Safety Verification***: Equipping robots with decision-making capabilities that assess the safety of learned systems, especially in the presence of neural network controlled systems.

***Skill-Based Learning***: Developing long-horizon skill acquisition from expert demonstration. This includes creating benchmark metrics and high-fidelity real2sim and sim2real transfer.

Please see my <a href="/frank_yang/assets/pdf/frank_cv.pdf" target="_blank">CV</a> for a full list of work, teaching, and other experiences.

## News
- **[May 2025]** Submitted Master Thesis <a href="/frank_yang/assets/pdf/MS_Thesis_Frank.pdf" target="_blank">"Safety-Assured Autonomy of Learning-Enabled Emobodied AI Agents"</a>!
- **[May 2025]** Submitted a paper on delayed offline RL to [NeurIPS 2025](https://neurips.cc/)
- **[Demember 2024]** - Submitted a paper on delayed IRL to [L4DC 2025](https://learning-for-dynamics.github.io/)
- **[October 2024]** - Invited talk to RV 2024
- **[August 2024]** - Submitted POLAR-express to [Embedded Systems Week 2024](https://esweek.org/) tool presentation (Winner of ESSC 2024)
- **[July 2024]** - One paper accepted to RV 2024
- **[June 2024]** - Started as a Robotic Learning Intern at [Stanford Vision and Learning Lab](https://svl.stanford.edu/)
- **[May 2023]** - One paper accepted to MMLS 2023

## Publications

S. Zhan, Q. Wu, **F. Yang**, X. Shi, C. Huang, Q. Zhu. Learning in Slow Motion: Adapting Offline Reinforcement Leanring with Online Delays. Neural Information Processing Systems, 2025. <a href="https://arxiv.org/abs/2506.00131" target="_blank">Paper</a> **(In submission)**

S. Zhan, Q. Wu, Z. Ruan, **F. Yang**, P. Wang, Y. Wang, R. Jiao, C. Huang, Q. Zhu. Inverse Delayed Reinforcement Learning. Learning for Dynamics and Control, 2025. <a href="https://arxiv.org/abs/2412.02931" target="_blank">Paper</a> **(In submission)**

**F. Yang**, S. Zhan, Y. Wang, et al. Case Study: Runtime Safety Verification of Neural Network Controlled System. Runtime Verification, 2024. <a href="https://arxiv.org/abs/2408.08592" target="_blank">Paper</a>

**F. Yang\***, Y. Wen\*. Efficient Encoding of Graphics Primitives with Simplex-based Structures. Midwest Machine Learning Symposium, 2023. <a href="https://arxiv.org/abs/2311.15439" target="_blank">Paper</a>

## Research Projects

<img src="/frank_yang/assets/img/Behavior.png" width="35%" align="left" style="margin:2rem 2rem 2rem 0rem"/>

<h3 style="margin: 0rem 0rem 1rem">Behavior 1K: A Human-Centered, Embodied AI Benchmark with 1,000 Everyday Activities and Realistic Simulation</h3>

Advised by: [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li)
<br clear="right">Sources: [Project](https://behavior.stanford.edu/behavior-1k) / [Paper](https://arxiv.org/abs/2403.09227)
<br clear="right">Development on BEHAVIOR-1K: 1000 embodied-AI robotic learning simulation benchmark built upon NVIDIA Omniverse engine; Decomposed complex, long-horizon tasks into learnable action primitives (pick, place, navigate); Implemented a collision-free action primitives execution pipeline using curobo
<br>

<img src="/frank_yang/assets/img/polar-express.png" width="35%" align="left" style="margin:2rem 2rem 4rem 0rem"/>

<h3 style="margin: 0rem 0rem 1rem">POLAR-Express: Efficient and Precise Formal Reachability Analysis of Neural-Network Controlled Systems</h3>

Advised by: [Qi Zhu](http://users.eecs.northwestern.edu/~qzhu/)
<br clear="right">Sources: [Paper](https://arxiv.org/abs/2408.08592) / [Tool](./assets/pdf/POLAR-express.pdf)
<br clear="right">Performed runtime safety verification case study with POLAR-express on Turtlebot3 in ROS2 simulation; Proposed online controller switch strategy for safety-critical control systems with neural networks; Designed an IRL framework that employs off-policy adversarial training to extract reward features from expert trajectories affected by observation delays
<br>

<img src="/frank_yang/assets/img/Encoding.png" width="35%" align="left" style="margin: 2rem 2rem 5rem 0rem"/>

<h3 style="margin: 0rem 0rem 1rem">Efficient Encoding of Graphics Primitives with Simplex-based Structures</h3>

Advised by: [Ying Wu](http://users.ece.northwestern.edu/~yingwu/)
<br clear="right">Source: [Paper](./frank_yang/assets/pdf/Encoding.pdf)
<br clear="right">Surveyed the encoding of graphics primitives proposed by “Instant NGP"; established theoretical foundations for simplex-based structure encodings and accelerated sample and interpolation speed on NeRF and SDF rendering with C++/CUDA kernels
<br>

<!-- <img src="/frank_yang/assets/img/3DIM.jpg" width="35%" align="left" style="margin: 2rem 2rem 4rem 0rem"/>

<h3 style="margin: 0rem 0rem 1rem">High-quality 3D imaging with Commodity Devices</h3>

Advised by: [Florian Willomitzer](https://www.optics.arizona.edu/person/florian-willomitzer) and [Oliver Cossairt](https://compphotolab.northwestern.edu/people/oliver-ollie-cossairt/)
<br clear="right">Created a python 3D imaging framework that facilitates non-technical users to discover micro-painting degradation in Kokomo glass test tiles; packaged a [3-step calibration sequence](https://pypi.org/project/GhostScan/)for Phase Measuring Deflectometry; benchmarked performance with FLIR camera on specular objects

<br clear="right"><a href="/frank_yang/assets/pdf/3DIM.pdf" target="_blank">Paper</a> -->

## Teaching

***Graduate TA*** for CS340: [Computer Networking](https://www.mccormick.northwestern.edu/computer-science/academics/courses/descriptions/340.html) taught by Alexandar Kuzmanovic, Winter 2023

***Graduate TA*** for CS310: [Scalable Software Architectures](https://www.mccormick.northwestern.edu/computer-science/academics/courses/descriptions/310.html) taught by Joe Hummel, Fall 2023

***Undergraduate TA*** for CS396: [Intro to Web Development](https://www.mccormick.northwestern.edu/computer-science/academics/courses/descriptions/396-6.html) taught by Sarah Van Wart, Spring 2022

***Project Manager*** for Institute of Electrical and Electronics Engineers, 2022

## Other Projects

<img src="/frank_yang/assets/img/quadrotor.jpg" width="35%" align="left" style="margin: 0rem 2rem 2rem 0rem"/>

<h3 style="margin: 0rem 0rem 1rem">Quadrotor Design and Control</h3>
_(Mar 2024 - Jun 2024)_

Source: [Code](https://github.com/yyf20001230/CS410) 
<br clear="right">Developed a WiFi-enabled quadrotor using Raspberry Pi and IMU; implemented PID control, safety measures, and joystick interfacing in C that allows stable manual flight control; integrated Vive Lighthouse with IR sensors to enable autonomous flight control with precise 3D positioning

<img src="/frank_yang/assets/img/reminiscia.jpg" width="35%" align="left" style="margin: 0rem 2rem 1rem 0rem"/>

<h3 style="margin: 0rem 0rem 1rem">Reminiscia</h3>
_(Dec 2022 - May 2023)_

Source: [Code](https://github.com/yyf20001230/reminiscia) 
<br clear="right">Implemented a multimodal text-to-image search application using pretrained vision-language models; employed Vision and CoreML to allow calculations of cosine similarity between text and image embeddings; distilled original 224MB CLIP model into an 85MB, 6-layer image encoder to improve inference speed
<br>
<br>
<br>


<img src="/frank_yang/assets/img/lie.jpg" width="35%" align="left" style="margin: 0rem 2rem 5rem 0rem"/>

<h3 style="margin: 0rem 0rem 1rem">Transformer-based Lie Detection</h3>
_(Feb 2022 - Jan 2023)_

Advised by: [Zach Wood Woughty](https://zachwd.com/)
<br clear="right">Source: [Code](https://github.com/yyf20001230/Lie_Detection)
<br clear="right">Conceptualized a vision-based transformer that detects lies from multimodal inputs with PyTorch; trained a transformer encoder from fine-tuning Inceptionv3; pinpointed 20 micro-gestures and facial AUs that most contribute to lying; resulted an out-of-sample lying classification of 76%


<!-- <img src="/frank_yang/assets/img/matcha.jpg" width="35%" align="left" style="margin: 2rem 2rem 4rem 0rem"/>

<h3 style="margin: 0rem 0rem 1rem">MatchaNU</h3>
_(Jun 2021 - Feb 2022)_

Launched a IOS application to assist Northwestern students with course planning and building navigation
<br>Integrated Google Geocoding API to generate building name from scrapped catalog into geocoordinates
<br>Integrated UIKit with LocationManager in SwiftUI to track location and provide to classrooms navigation
<br> Used by over 1000 Northwestern undergraduates every quarter; making updates from quarterly testing

<br clear="right" style="margin: 1rem 0rem 2rem">[Code](https://github.com/yyf20001230/matchaNU)
<br>
<br> -->

<!-- <img src="/frank_yang/assets/img/lightfield.jpg" width="35%" align="left" style="margin: 2rem 2rem 6rem 0rem"/>

<h3 style="margin: 0rem 0rem 1rem">Single-Len Lightfield imaging</h3>
_(Jul 2021 - Feb 2022)_

Introduced an alternative to a light-field camera that synthesizes camera focus point after a video is taken
<br>Researched capturing the light-field from a camera with known parameter with OpenCV
<br>Tested with mirrorless-cam experiments and decreased the functional cost of a light-field camera by 3000%

<br clear="right" style="margin: 1rem 0rem 2rem">[Code](https://github.com/yyf20001230/LightField)
<br> -->

## Work Experiences

***Software Engineer Intern @ [Target](https://www.target.com)*** _(June 2023 - Aug 2023)_

Developed a Golang application within a Vela CI/CD pipeline to enforce security and compliance standards
<br>Integrated Postgres with RestAPI for build lifecycle and versioning information retrieval and storage

***Lead Tech Engineer @ [Skuy](https://www.skuy.app/)*** _(Apr 2022 - Jun 2024)_

Built a college community network app startup, amassed 1000+ users on both the App Store and Google Play
<br>Led a 2-months database migration from Heroku to Firebase for service growth and stability
<br>Configured CI/CD pipeline on Expo for IOS Pod and Android Gradle builds

***Software Development Engineering Intern @ [Amazon](https://www.amazon.com/)*** _(Jun 2022 - Sep 2022)_

Implemented a Sagemaker site that provides benchmarked health & architecture evaluations for ML models
<br>Presented a demo to Sagemaker engineers; received candidacy to beta-launch model cards on AWS Re:Invent

## Skills

***Languages***: Python, Go, TypeScript, SwiftUI, HTML/CSS/JavaScript, C++
<br>***Robotic Learning***: ROS2, Torch, CUDA, TensorFlow, OpenCV
<br>***Web/Mobile Development***: React, React Native, Flask, Redux, Node, ESLint, Cypress
<br>***DevOps***: RestAPI, AWS, Firebase, Heroku, Elastic Beanstalk, Git, Vela, Docker, MySQL, PostgresSQL

## Cimematography

<img src="/frank_yang/assets/img/photography.png" width="40%" align="left" style="margin:2rem 4rem 5rem 0rem"/>

<br clear="right"> Outside of school, I am a freelance photographer taking landscape, portrait, and graduation photos. In my creative endeavor, I am a cinematographer working on film projects such as Applause For A Cause and TEDx. I am committed to creating cinematic lighting and true-story shots that evokes emotion. Check out my [portfolio](https://sashimiphotos.com) for my fun side!

![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=http%3A%2F%2Ffrankyang.me&count_bg=%23FFA148&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)

[CV]: https://drive.google.com/file/d/1lxpvsV7zgDOGkaYI4jsujNtcj7tX1Utx/view?usp=sharing
[blog]: https://hydejack.com/blog/
[portfolio]: https://hydejack.com/projects/
[resume]: https://hydejack.com/resume/
[download]: https://hydejack.com/download/
[welcome]: https://hydejack.com/
[forms]: https://hydejack.com/forms-by-example/

[features]: https://hydejack.com/#features
[news]: https://hydejack.com/#build-an-audience
[syntax]: https://hydejack.com/#syntax-highlighting
[latex]: https://hydejack.com/#beautiful-math
[dark]: https://hydejack.com/blog/hydejack/2018-09-01-introducing-dark-mode/
[search]: https://hydejack.com/#_search-input
[grid]: https://hydejack.com/blog/hydejack/

[lic]: LICENSE.md
[pro]: licenses/PRO.md
[docs]: https://hydejack.com/docs/
[ofln]: https://hydejack.com/docs/advanced/#enabling-offline-support
[math]: https://hydejack.com/docs/writing/#adding-math

[kit]: https://github.com/hydecorp/hydejack-starter-kit/releases
[src]: https://github.com/hydecorp/hydejack
[gem]: https://rubygems.org/gems/jekyll-theme-hydejack
[buy]: https://gum.co/nuOluY
[nfy]: https://app.netlify.com/start/deploy?repository=https://github.com/hydecorp/hydejack-starter-kit
[dtn]: https://www.netlify.com/img/deploy/button.svg

[gpss]: https://developers.google.com/speed/pagespeed/insights/?url=https://hydejack.com/
[hy-push-state]: https://hydecorp.github.io/hy-push-state/
[hy-drawer]: https://hydecorp.github.io/hy-drawer/
[rouge]: http://rouge.jneen.net
[katex]: https://khan.github.io/KaTeX/
[mathjax]: https://www.mathjax.org/
[tinyletter]: https://tinyletter.com/