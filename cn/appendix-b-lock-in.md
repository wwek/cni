#附录B 锁定

关于使用云提供商和避免供应商锁定存在很多争议。这场辩论往往比实际更具意识形态。

锁定通常是工程师和管理层关心的问题。应该以与选择编程语言或框架相同的方式将其作为应用程序的风险来权衡。编程语言和云提供商的选择是锁定的形式，工程师有责任了解风险并了解风险何时可以接受。

当您选择供应商或技术时，请记住以下几点：

 - 锁定是不可避免的。
 - 锁定是一种风险，但并不总是很高。
 - 不要外包思维。

## 锁定是不可避免的

在技术上有两种类型的锁定：

**技术锁定**

在开发堆栈中处理较低的决策

**供应商锁定**

大多数情况下，处理作为项目一部分使​​用的服务和软件（供应商锁定还可能包括硬件和操作系统，但我们只关注服务）

### 技术锁定

开发人员将选择他们熟悉的技术或为正在开发的应用程序提供最大利益的技术。这些技术可以从供应商提供的技术（例如.NET和Oracle数据库）到开源软件（例如Python和PostgreSQL）。

在此级别提供的锁定通常要求符合API或规范，这将影响应用程序的开发。有时候可以选择所选择的技术，但是它们通常具有很高的转换成本，因为技术对应用程序的设计有很大影响。

### 供应商锁定

供应商，如云提供商，是一种不同形式的锁定。在这种情况下，您正在耗用供应商的资源。这可以是基础设施资源（例如，计算和存储），或者它可以是托管软件（例如，Gmail）。

消耗资源的堆栈越高，应该从消耗的资源（例如Heroku）获得的价值就越高。高层次资源是从底层资源中抽离出来最多的，并使产品的生产速度更快。

## 锁定是一种风险

技术锁定通常是一次性决定或与供应商达成使用该技术的协议。如果您不再与供应商达成支持协议，则您的软件不会立即中断;它只是变得自我支持。

开源软件可以减少来自技术的锁定量，但并不能消除它。使用开放标准可以进一步减少锁定，但了解开放标准与开放源代码之间的差异很重要。

仅仅因为别人编写代码并不能使其成为标准。同样，专有系统可以形成非官方标准，允许从它们迁移出去（如AWS S3）。

供应商锁定的原因通常不仅仅是技术锁定，而是因为供应商锁定的风险高于技术。如果您不支付供应商，您的申请将停止运行;你不再能够访问你所支付的资源。

如前所述，供应商服务提供更多价值，因为它们允许产品开发不需要所有较低级别的实现。不要避免托管服务来消除风险;你应该像对待其他任何事情一样权衡服务的风险和回报。

如果服务提供标准接口，则风险非常低。界面越是自定义，或者产品越独特，切换的风险就越高。

## 不要外包思维

本书的目标之一就是帮助你自己做出决定。不要盲目听取其他人的意见或报告，不知道咨询的内容以及它如何适用于您的情况。

如果您可以通过使用托管云服务更快地交付产品，则应该选择一个供应商并开始使用它们。虽然衡量风险是好的，但对具有类似解决方案的多家供应商进行无尽的争论，并且自己构建服务并不能很好地利用时间。

如果多个供应商提供类似的服务，请选择最容易采用的服务。开始使用该服务后，限制将很快显现。选择供应商时最重要的因素是选择一个与您具有相同创新步伐的供应商。

如果供应商的创新速度比您快，那么您将无法利用其最新技术，并且可能不得不花大量时间从旧技术中迁移。如果供应商的创新过于缓慢，那么您将不得不根据供应商提供的内容构建自己的抽象，而且您不会专注于您的业务目标。

为了保持竞争力，您可能需要消耗尚未拥有标准或替代品的资源（例如，新的和实验性的服务）。不要因为他们会让你陷入这项服务而感到害怕。重视保持竞争力或失去市场份额的风险，您的竞争对手可能会更快地进行创新。

了解您无法避免的风险以及您的业务有多大风险。做出最大化回报并将风险降至最低的决策
