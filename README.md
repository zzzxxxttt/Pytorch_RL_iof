# Reinforcement learning algorithms **in one file**

This repository is for those who want to implement the RL algorithms after reading the corresponding papers.
All the algorithms are encapsulated in one file, which can let you focus more on the algorithm itself.

## Requirements:
- python>=3.5
- pytorch>=0.4.0
- drawnow

### 1. DDPG for MountainCarContinuous-v0:
![image](https://github.com/zzzxxxttt/pytorch_rl_iof/blob/master/figures/ddpg_mtcar.png)

- Code mainly adopted from https://github.com/lirnli/OpenAI-gym-solutions/blob/master/Continuous_Deep_Deterministic_Policy_Gradient_Net/DDPG%20Class%20ver2.ipynb
- I just rewrite the code using pytorch, and fixed a small bug in the original code when updating the actor.

### 2. A2C for MountainCarContinuous-v0:
![image](https://github.com/zzzxxxttt/pytorch_rl_iof/blob/master/figures/a2c_mtcar.png)

- Code mainly adopted from https://gist.github.com/Ashioto/10ec680395db48ddac1ad848f5f7382c#file-actorcritic-py
- I just rewrite the code using pytorch. As mentioned by the original author, this a2c code is extremely unstable, if you find it does not work, just kill the process and restart training :)

### 3. REINFORCE for CartPole-v0:
![image](https://github.com/zzzxxxttt/pytorch_rl_iof/blob/master/figures/reinforce_cartp.png)

- Code mainly adopted from https://github.com/JamesChuanggg/pytorch-REINFORCE

### 4. TRPO for MountainCarContinuous-v0:
![image](https://github.com/zzzxxxttt/pytorch_rl_iof/blob/master/figures/trpo_mtcar.png)

- Code mainly adopted from https://github.com/ikostrikov/pytorch-trpo
- This piece of code is a little bit complicated, I've tried my best to place everything (LBFGS, conjugate gradient, line search, GAE, ...) in one file.
- ~ 300 lines, not so horrible, right?

### 5. PPO for MountainCarContinuous-v0:
![image](https://github.com/zzzxxxttt/pytorch_rl_iof/blob/master/figures/ppo_mtcar.png)

- Code mainly adopted from https://github.com/tpbarron/pytorch-ppo

