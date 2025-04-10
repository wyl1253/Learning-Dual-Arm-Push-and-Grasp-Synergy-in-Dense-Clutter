# Learning-Dual-Arm-Push-and-Grasp-Synergy-in-Dense-Clutter

## ⚠️⏳ Work in Progress!

> **⚠️ This project is NOT complete yet.**  
> ⏳ *I'll finish it soon — currently busy with relocation.*  
>  
> 🙏 Thanks for your patience!


### About this repository

This repository provides the paper's implementation and examples for generating various cluttered scenes in Isaac Gym.

If you are unable to develop your manipulator URDFs, you can refer to the following open-source repositories for ready-to-use robot models:

- [OmniIsaacGymEnvs-UR10Reacher](https://github.com/j3soon/OmniIsaacGymEnvs-UR10Reacher)  
- [ur5_isaac_simulation](https://github.com/caiobarrosv/ur5_isaac_simulation)  
- [pmbs](https://github.com/arc-l/pmbs)

### Installation

Download the Isaac Gym Preview 4 release from the [website](https://developer.nvidia.com/isaac-gym), then
follow the installation instructions in the documentation. We highly recommend using a conda environment 
to simplify setup.

Ensure that Isaac Gym works on your system by running one of the examples from the `python/examples` 
directory, like `joint_monkey.py`. Follow the troubleshooting steps described in the Isaac Gym Preview 4
install instructions if you have any trouble running the samples.

Once Isaac Gym is installed and samples work within your current Python environment, install this repo:

```bash
pip install -e .
```
