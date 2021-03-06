## 软件生命周期
>  软件生命周期 (Systems Development Life Cycle, SDLC)

### 什么是软件生命周期
	软件生命周期又称为软件生存周期或系统开发生命周期，是软件的产生知道报废的生命周期，周期内有问题定义、可行性分析、总体描述、系统设计、编码、调试和测试、验收与运行、维护升级到报废等阶段，这种按时间分程的思想方法是软件工程中的一种思想原则，即按部就班、足部推进，每个阶段都要有定义、工作、审查、形成文档以供交流或备查，一提供软件的质量。单随着新的面向对象的设计方法和技术的成熟，软件生命周期设计方法的指导意义正在逐步减少。
	
	生命周期的每一个周期都有确定的任务，并产生一定规格的文档（资料），提交给下一个周期作为继续工作的依据。按照软件的生命周期，软件的开发不再只单单强调“编码”，而是概括了软件开发的全过程。软件工程要求每一周期工作的开始只能必须是建立在前一个周期结果“正确”前提上的延续；因此，每一周期都是按“活动 ── 结果 ── 审核 ── 再活动 ── 直至结果正确”循环往复进展的

### 软件生命周期的七个阶段

1. 问题的定义及规划
	此阶段是软件开法方与需求方共同讨论，主要确定软件的开发目标及其可行性。

2. 需求分析
	在确定软件开发可行的情况下，对软件需求实现的各个功能进行详细分析。需求分析阶段是一个重要的阶段，这一阶段做得好，降维整个软件开发项目的成功打下良好的基础。“唯一不变的是变化本身”。同样需求也是在真个软件开发过程中不断变化和深入的，因此我们必须制定需求变更计划来应付这种变化，以保护真个项目的顺利进行。

3. 软件设计
	此阶段主要根据需求分析的结果，对整个软件系统进行设计，入性通框架设计，数据库设计等等。软件设计一般分为总体设计和详细设计。好的软件设计降维软件程序编写打下良好的基础。

4. 程序编码
	此阶段是讲软件设计的结果转换成计算机可运行的程序代码。在程序编码必须要制定统一、符合标准的编写规范。以保证程序的可读性，易维护性，提高程序的运行效率。

5. 软件测试
	在软件设计完成后要经过严密的测试，以发现软件在整个设计过程中存在的问题并加以纠正。整个测试过程主要分单元测试、组装测试以及系统测试三个阶段进行。测试的方法主要有白盒测试和黑盒测试两种。在测试过程中需要建立详细的测试计划并严格按照测试计划进行测试，以减少测试的随意性。

6. 系统转换
	将作业由旧系统转化新系统，也就是说运行系统的方法，转换方法有平行、分批、分发、立即、试验五种方法

7. 运行维护
	软件维护是软件生命周期中持续时间最长的阶段。在软件开发完成并投入使用后，由于多方面的原因，软件不能继续适应用户的需求。要延续软件的使用寿命，就必须对软件进行维护。软件维护包括纠错性维护和改进性维护两个方面。

### 软件生命周期的模型
	从概念提出的那一刻起，软件产品就进入了软件生命周期。在经理需求、分析、设计、实现、部署后，软件将被使用并进入维护阶段，直接最后由于缺少维护费用而逐渐消亡。这样的一个过程，称为 "生命周期模型"(Life Cycle Model)。
	典型的几种生命周期模型包括瀑布模型、快速原型模型、迭代模型。

- 瀑布模型(Waterfall Model)
	文档驱动，整个过程都需要编制文档并获得软件质量保证小组的认可才能进入下一阶段。

- 迭代式模型RUP(Rational Unified Process, 统一软件开发过程，统一软件过程)
	迭代驱动，将所有阶段细分为迭代，每次迭代都是最终产品的一个子集。

- 快速原型模型(Rapid Prototype)
	在功能上等介于产品的一个子集。根据客户需求快速完成一个可以演示的产品。这个产品实现（最重要的）部分功能。

事实上，其实现在的软件组织中很少说标准的采用那一种模型的。模型和实用还是有很大的区别。