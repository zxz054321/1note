<h1 align="center">1note</h1>


## 设计目标

### Markdown

以 HTML 为底层源码的编辑器，历经多年发展至今，仍无法解决格式错乱、难以维护的问题，这是 HTML 编辑器难以逾越的鸿沟。当前最有希望克服 HTML 编辑器缺点的，就是以 Markdown 为底层源码的编辑器了。

但目前鲜有完全无需理会 Markdown 源码的所见即所得 Markdown 编辑器，这是 1note 需要解决的问题。

### 轻量笔记

1note 不打算成为《印象笔记》这种重量级的笔记应用，Apple 的《备忘录》是 1note 最主要的学习榜样。跟 Apple 的《备忘录》不同的是，《备忘录》只为 Apple 设备提供，1note 为所有联网的设备提供。

### 易于部署

1note 在现代 Web 生态的基础上，结合自动化技术和部署脚本，尽可能地简化部署工作。

### 易于迁移

1note 尽可能地减少环境依赖，如此可轻松在不同平台之间迁移。

### 不绑定云

1note 避免使用云厂商的特有非通用服务，以免被“某云”绑死，导致难以迁移去不同的云厂商。



## 七大原则

### 成熟稳定

在可选择的情况下，1note 只选用已经成熟且稳定的技术方案。如迫不得已只有尚未成熟稳定的技术可选，1note 将谨慎考虑。

### 缓慢迭代

与互联网时兴的“快速迭代”策略相反，1note 采用“缓慢迭代”策略：平时少更新，只有经过反复论证、非常必要、非常成熟稳定的更改，会发布到生产环境。

### 懒惰运维

为了节省长期精力，1note 竭力减少人工运维工作量，这通过精简的环境依赖和自动化运维手段实现。

### 最小架构

1note 反对为了“高大上”而将系统架构复杂化，1note 的架构必须是最精简的，引入架构中的组件必须是最必要的。

### 极致体验

在体验上寸土必争，这是 1note 存在的意义。

### 处处克制

任何时候，面对任何新想法、新需求、新技术，1note 都必须保持克制。除了经反复论证之后仍认为非常有必要的。

### 脚踏实地

对于任何目标，1note 都不奢望一步到位。1note 始终坚持仰望星空，脚踏实地，一步一个脚印，不骄不躁，直到目标达成。



## 技术选型

**PHP 7.2**（依照目前最新的 Laravel 6.0 要求的最低 PHP 版本而定）

**Laravel 5.7**（最新的稳定版原则）
