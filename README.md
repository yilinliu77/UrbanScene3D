


# The official website for UrbanScene3D has moved to https://vcc.tech/UrbanScene3D. You could find all the resources on this website.

# UrbanScene3D

This is the introductions of UrbanScene3D: A Large Scale Urban Scene Dataset and Simulator. [[paper](https://arxiv.org/abs/2107.04286)], [[Project page](https://vcc.tech/UrbanScene3D/)]

<img src="misc/overview.jpg">

<p align="center">Figure 1: Overview of UrbanScene3D.</p>



We present a large scale urban scene dataset associated with a handy simulator based on Unreal Engine 4 and AirSim, which consists of both man-made and real-world reconstruction scenes in different scales, referred to as *[UrbanScene3D ](https://vcc.tech/UrbanScene3D)*. The manually made scene models have compact structures, which are carefully constructed/designed by professional modelers according to the images and maps of target areas; see the first row of Figure 1 for a glance. In contrast, *UrbanScene3D* also offers dense, detailed scene models reconstructed by aerial images through multi-view stereo (MVS) techniques. These scenes have realistic textures and meticulous structures; see e.g., the second row of Figure 1. We have also released the originally captured aerial images that have been used to reconstruct the 3D scene models, as well as a set of 4K video sequences, all of which would facilitate designing algorithms, such SLAM and MVS; please check some samples shown in the third and fourth rows of Figure 1.


<!-- [![Watch the video]()](https://user-images.githubusercontent.com/25240333/126533739-740c81c1-8edd-42ab-9b17-0dc871475064.mp4) -->

<div align=center><img src="misc/gif1.gif"></div>



<p align="center">Video 1: Touring a virtual city scene. Note that users can obtain the corresponding CAD models associated with instance segmentation.</p>



<div align=center><img src="misc/gif2.gif"></div>




<p align="center">Video 2: Touring the real-world scenes. Note that these scenes are reconstructed by real-world aerial images, thus they have detailed geometries, structures and realistic textures. The instance segmentation is available as well.</p>



<div align=center><img src="misc/gif3.gif"></div>




<p align="center">Video 3: A real-world model reconstructed with aerial images captured from optimized 3D views.</p>



<div align=center><img src="misc/gif4.gif"></div>




   <p align="center">Video 4: A sample of aerial videos aimed at 3D urban scene acquisition.</p>



<div align=center><img src="misc/gif5.gif"></div>




   <p align="center">Video 5: Applications of our dataset and simulator, e.g., autonomous driving, drone navigation, and intelligent aerial acquisition.</p>




## Downloads

Note that all DATA and CODE are **free for Research and Education Use ONLY**.
Please cite our [paper](https://arxiv.org/abs/2107.04286) if you use any part of our ALGORITHM, CODE, DATA or RESULTS in any publication.

- Download via [**Baidu Netdisk**](https://pan.baidu.com/s/1ft1_5kFckPv7BTdMPlC4oA) (code: vccc, recommend)
- Download via [**Dropbox**](https://www.dropbox.com/sh/tx8n48ayjxjp9su/AACoNqF8VOosMvHXL1sDl4Qaa?dl=0) (faster outside China, recommend)
- Download via [**HTTP**](https://nas.moutong.org:4430/UrbanScene3D-VCC.zip)
- Download via FTP (ftp://nas.moutong.org/dataset/UrbanScene3D-VCC.zip)
- Dataset Description Download via [**arXiv**](https://arxiv.org/abs/2107.04286)

(Note: In Baidu Netdisk and Dropbox, we have compressed the files in volume. Please download all the files and extract the main compression package)



## Requirements

The released zip file contains the unreal project of the above proposed urban scenes. As Video 5 shown, users can use either pure [**Unreal Engine**](https://docs.unrealengine.com/en-US/index.html) or [**AirSim client (both in C++ or python)**](https://microsoft.github.io/AirSim/apis/) to capture their desired data. The ground truth textured meshes and their relevant poses are also provided in the Unreal project.

​	Required packages:

- Unreal Engine 4 (4.24 is recommended)
- C++ or Python
- AirSim(Optional)



## Reference

If you find UrbanScene3D useful in your research, please consider citing:

```
@article{UrbanScene3D,
title={UrbanScene3D: A Large Scale Urban Scene Dataset and Simulator},
author={Yilin Liu and Fuyou Xue and Hui Huang},
eprint={2107.04286},
archivePrefix={arXiv},
year={2021},
}
```

