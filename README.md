# QuadrotorFly四旋翼无人机动力学模型

主要目的是开发一个用于无人机动力学仿真的简单易用、功能相对齐全的仿真环境。

# 主要功能

## 模型功能

- 四旋翼基本动力学模型，即电机推力到角速度、速度的动力学
- 干扰模型，外部给的风扰和均值固定的随机噪声
- 执行器动力学模型，考虑电机模型，从控制输入（百分比）到推力的动力学
- 机型选择，'x'型无人机或者'+'型无人机
- 内置参考的控制器，现有pid

## 仿真功能
- 支持随机初始位置、固定初始位置两种模式
- 采样时间可设定，状态更新方式采用4阶龙格库塔方法
