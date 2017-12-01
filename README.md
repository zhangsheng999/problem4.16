# problem4.16
## 题目：Carry out a true three-body simulation in which t he motions Of Earth, Jupiter, and the Sun are all calculated. Since all t h ree bodies are now in mo t ion ， it is useful to take the center Of mass Of t he three-body system the origin, rather than the position Of Sun. We also suggest that you give S u n an initial velocity which makes the total momentum Of the system exactly zero （So that the center of mass will remain fixed） ，study the motion Of Earth with different initial conditions. Also, try increasing the mass Of Jupiter to 10 ， 100 ， and 1000 times its true mass.
## 题目大意：本次实验主要是研究太阳，地球和木星三体的运动情况，由于三者均在运动，所以采取三体的质心系作为坐标系，初始时刻给太阳一个初速度，以便使总的角动量为0，以此简化问题，然后研究对于不同初始条件的地球的运动，改变木星质量为原来的10,100,1000等倍数时对地球的运动情况。

### 由此初始时刻给太阳一个初速度，使总角动量为0，并且以太阳为原点

[代码](https://github.com/zhangsheng999/22222/blob/master/%E6%96%B0%E5%BB%BA%E6%96%87%E6%9C%AC%E6%96%87%E6%A1%A3.txt)

### 一，木星质量为真实质量时

![](https://github.com/zhangsheng999/22222/blob/master/1000.png?raw=true)

### 二，木星质量为其真实质量的10倍时

![](https://github.com/zhangsheng999/22222/blob/master/100.png?raw=true)

### 三，木星质量为其真实质量的100倍时

![](https://github.com/zhangsheng999/22222/blob/master/10.png?raw=true)

### 四，木星质量为其真实质量的1000倍时

![](https://github.com/zhangsheng999/22222/blob/master/1.png?raw=true)


## 结论：在木星质量不变时地球轨道是稳定的，几乎不受影响，但是木星轨道在在这之后产生了极大的偏离；变为原来的10倍时，可以看出地球，包括太阳都在发生向着某个方向的进动，木星轨道依旧偏离较大；变为原来的100倍时，整个系统都极不稳定。变为原来的1000倍时，这时木星质量与太阳处于同一个量级，系统明显表现出混沌状态。 木星质量不变时，地球绕着太阳运动，并且由于收到木星重力作用，会做进动，而且随着木星质量的增加，进动越来越明显，当木星质量变得足够大，甚至和太阳数量级相同时，地球可能会和太阳或者木星发生碰撞。
  
### 致谢：感谢华扬以及丁冬冬同学，借鉴了代码与报告。
