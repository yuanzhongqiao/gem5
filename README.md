<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-the-gem5-simulator" class="anchor" aria-hidden="true" tabindex="-1" href="#the-gem5-simulator"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gem5模拟器</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是 gem5 模拟器的存储库。</font><font style="vertical-align: inherit;">它包含模拟器以及所有测试和回归的完整源代码。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gem5模拟器是一个用于计算机系统架构研究的模块化平台，涵盖系统级架构以及处理器微架构。</font><font style="vertical-align: inherit;">它主要用于评估新的硬件设计、系统软件更改以及编译时和运行时系统优化。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="http://www.gem5.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主要网站可以在http://www.gem5.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到</font><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-testing-status" class="anchor" aria-hidden="true" tabindex="-1" href="#testing-status"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试状态</font></font></h2>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：这些测试在 gem5 的开发分支上运行：
 https: </font></font><a href="https://github.com/gem5/gem5/tree/develop"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//github.com/gem5/gem5/tree/develop</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><a href="https://github.com/gem5/gem5/actions/workflows/daily-tests.yaml"><img src="https://github.com/gem5/gem5/actions/workflows/daily-tests.yaml/badge.svg" alt="每日测试" style="max-width: 100%;"></a>
<a href="https://github.com/gem5/gem5/actions/workflows/weekly-tests.yaml"><img src="https://github.com/gem5/gem5/actions/workflows/weekly-tests.yaml/badge.svg" alt="每周测试" style="max-width: 100%;"></a>
<a href="https://github.com/gem5/gem5/actions/workflows/compiler-tests.yaml"><img src="https://github.com/gem5/gem5/actions/workflows/compiler-tests.yaml/badge.svg" alt="编译器测试" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-getting-started" class="anchor" aria-hidden="true" tabindex="-1" href="#getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个好的起点是</font></font><a href="http://www.gem5.org/about" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.gem5.org/about</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，有关构建模拟器和入门的更多信息，请参阅</font></font><a href="http://www.gem5.org/documentation" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.gem5.org/documentation</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和
</font></font><a href="http://www.gem5.org/documentation/learning_gem5/introduction" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.gem5。 org/documentation/learning_gem5/introduction</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-building-gem5" class="anchor" aria-hidden="true" tabindex="-1" href="#building-gem5"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建筑宝石5</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要构建 gem5，您将需要以下软件：g++ 或 clang、Python（Python 解释器中的 gem5 链接）、SCons、zlib、m4，如果您需要跟踪捕获和回放支持，最后还需要 protobuf。</font><font style="vertical-align: inherit;">有关这些工具最低版本的更多详细信息，</font><font style="vertical-align: inherit;">请参阅
</font></font><a href="http://www.gem5.org/documentation/general_docs/building" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.gem5.org/documentation/general_docs/building 。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解决所有依赖关系后，执行
</font></font><code>scons build/ALL/gem5.opt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以构建包含所有 gem5 ISA 的 gem5 二进制文件 ( ) 的优化版本</font></font><code>gem5.opt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">如果您只想编译 gem5 以包含单个 ISA，则可以替换</font></font><code>ALL</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 ISA 的名称。</font><font style="vertical-align: inherit;">有效选项包括</font></font><code>ARM</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>NULL</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>MIPS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>POWER</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>RISCV</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>SPARC</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>X86</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
完整的选项列表可以在 build_opts 目录中找到。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关构建 gem5 的更多信息，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://www.gem5.org/documentation/general_docs/building" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.gem5.org/documentation/general_docs/building 。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-the-source-tree" class="anchor" aria-hidden="true" tabindex="-1" href="#the-source-tree"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">源树</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主要源代码树包括以下子目录：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">build_opts：gem5 的预制默认配置</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">build_tools：gem5 构建过程内部使用的工具。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">configs：示例模拟配置脚本</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ext：构建 gem5 所需的不太常见的外部包</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">include：包含供其他程序使用的文件</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">site_scons：构建系统的模块化组件</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">src：gem5模拟器的源代码。</font><font style="vertical-align: inherit;">C++ 源代码、Python 包装器和 Python 标准库都可以在此目录中找到。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">system：一些用于模拟系统的可选系统软件的来源</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试：回归测试</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">util：有用的实用程序和文件</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-gem5-resources" class="anchor" aria-hidden="true" tabindex="-1" href="#gem5-resources"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gem5 资源</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要运行全系统模拟，您可能需要编译的系统固件、内核二进制文件和一个或多个磁盘映像，具体取决于 gem5 的配置以及您尝试运行的工作负载类型。</font><font style="vertical-align: inherit;">其中许多资源可以从</font></font><a href="https://resources.gem5.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://resources.gem5.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关 gem5 资源的更多信息，请访问
</font></font><a href="https://www.gem5.org/documentation/general_docs/gem5_resources/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.gem5.org/documentation/general_docs/gem5_resources/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-getting-help-reporting-bugs-and-requesting-features" class="anchor" aria-hidden="true" tabindex="-1" href="#getting-help-reporting-bugs-and-requesting-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取帮助、报告错误和请求功能</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们为用户和开发人员提供各种渠道来获取帮助、报告错误、请求功能或参与社区讨论。</font><font style="vertical-align: inherit;">以下是我们建议使用的一些最常见的方法。</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 讨论</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：GitHub 讨论页面。</font><font style="vertical-align: inherit;">这可用于开始讨论或提出问题。</font><font style="vertical-align: inherit;">可在
</font></font><a href="https://github.com/orgs/gem5/discussions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/orgs/gem5/discussions</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Issues</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：用于报告错误或请求功能的 GitHub 问题页面。</font><font style="vertical-align: inherit;">可在</font></font><a href="https://github.com/gem5/gem5/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/gem5/gem5/issues</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jira 问题跟踪器</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：用于报告错误或请求功能的 Jira 问题跟踪器。</font><font style="vertical-align: inherit;">可在</font></font><a href="https://gem5.atlassian.net/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://gem5.atlassian.net/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Slack</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：一个Slack服务器，有多种渠道供gem5社区进行各种讨论。</font><font style="vertical-align: inherit;">请访问
</font></font><a href="https://www.gem5.org/join-slack" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.gem5.org/join-slack</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加入。</font></font></li>
<li><strong><a href="mailto:gem5-users@gem5.org"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gem5-users@gem5.org</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：gem5 用户提问或开始讨论的邮件列表。</font><font style="vertical-align: inherit;">要加入邮件列表，请访问
</font></font><a href="https://www.gem5.org/mailing_lists" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.gem5.org/mailing_lists</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><strong><a href="mailto:gem5-dev@gem5.org"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gem5-dev@gem5.org</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：gem5 开发人员提出问题或开始讨论的邮件列表。</font><font style="vertical-align: inherit;">要加入邮件列表，请访问
</font></font><a href="https://www.gem5.org/mailing_lists" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.gem5.org/mailing_lists</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributing-to-gem5" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing-to-gem5"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 gem5 做出贡献</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们希望您喜欢使用 gem5。</font><font style="vertical-align: inherit;">在适当的时候，我们建议您对项目的贡献进行收费。</font></font><a href="https://www.gem5.org/contributing" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.gem5.org/contributing</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以帮助您入门。</font><font style="vertical-align: inherit;">其他信息可以在 CONTRIBUTING.md 文件中找到。</font></font></p>
</article></div>