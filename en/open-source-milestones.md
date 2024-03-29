---
outline: deep
---
# 2023 OSS Chronicle

## Overview

Why do we include a considerable amount of international open-source news in the Open Source Chronicle section of the China Open Source Annual Report? These are the significant events that Chinese open-source enthusiasts must be aware of, and they are the crucial events that impact China's open-source community or will do so in the future.

The Open Source Chronicle reflects the foremost open-source events of 2023 that have captured the attention of editorial volunteers from diverse backgrounds. The overarching theme underpinning our thought process is exploring open-source technologies' vast potential and accompanying benefits for a wide range of stakeholders. As editorial volunteers, we are committed to ensuring that our coverage of this landmark event is comprehensive, objective, and informative, enabling our readers to understand better the latest trends and developments in the open-source domain.

* Disruptive innovations in global "**Open-Source Technologies**" such as artificial intelligence and machine learning, are the main theme throughout the Chronicle;
* Global conflicts resulting from geopolitical dynamics indirectly impact "**Open-Source Ecology**", regardless of East vs. West;
* This has resulted in a shift towards "**Open-Source Governance**" in all areas, including regions, law, trade, and communities;
* whereas the topic "**Open Source Security**" is considered a top priority;
* The growth of "**Open Source Commercialization**" is a promising trend, and though 2023 may pose some challenges, it's encouraging to know that there is an abundance of open-source startups thriving worldwide, including in China.;
* In today's world, technology, ecology, governance, and commercialization are undergoing significant changes. This has made "**Open Source Education**" a crucial foundation for exploring new possibilities. Artificial intelligence is a prime example of disruptive innovation that requires persistent research and a robust higher education system to achieve its current level of success.
* The last part of the "**Open Source Ranklists, Papers and Reports**" is like a delightful dessert after dinner. It will be fascinating to observe if it provides valuable insights and accurately predicts the future of open-source development in China. We can only know for sure by the end of 2024.


This year, AI is present in all categories. A holistic approach is necessary for full comprehension.

In brief, we stand on the brink of a world where AI will transform the way things work. We hope to meet you at next year's Open Source Chronicle!

## 1. Open Source Technology Chronicle

### 1.1 Artificial Intelligence and Large Models

- **ZHIPU AI - GLM**
ZHIPU AI has open-sourced the ChatGLM-6B series, ChatGLM-6B is an open-source dialogue language model that supports bilingual Q&A. In addition, ZHIPU AI has open-sourced VisualGLM-6B (CogVLM), a multi-modal dialogue model, which combines the capabilities of image processing and natural language processing to support both Chinese and English dialogues, aiming to provide a richer and more intuitive interactive experience.
- **Baichuan**
Over the past year, Baichuan has released several versions of large models, including Baichuan-7B. Later, they launched the 13B model and the Baichuan2 series of models, and made the base and chat versions open-source. One of the latest models, Baichuan2-192K, has a large size and a context window length of 192K.
- **Intern general large model system**
Shanghai Artificial Intelligence Laboratory (AIL) released the newly upgraded "Intern General Large Model System", which includes three basic models, including Intern Multimodal - Large Model, InternLM - Large Language Model and InternLandMark - Large-scale 3D Neural Radiance Field, as well as the first Full-Chain Open Source System for the research, development and application of large models.
- **Alibaba - Qwen**
Alibaba open-sourced the 7B model of Tongyi QianWen (Qwen), and then successively open-sourced the base and chat models of 1.8B, 14B, and 72B, and provided the quantised versions of the corresponding int4 and int8. In the multimodal scenarios, QianWen also open-sourced the two multimodal models of vision and speech, qwen-vl and qwen-audio.
- **Kunlun - Skywork**
Kunlun Inc. released the 10 billion large language model "Skywork" Skywork-13B series and open-sourced the 600GB, 150B Tokens large and high-quality open-source Chinese dataset. Skypile/Chinese-Web-Text-150B dataset.
- **RWKV**
RWKV has been continuously open-sourced since its release as a non-Transformer structured model for large languages. In 2023, RWKV has released multiple versions and entered LF AI & Data for incubation.
- **Inspur - Yuan 2.0**
Inspur Electronic Information Industry Co., Ltd. officially released "Yuan 2.0", a 100-billion base model. This series of models is fully open-sourced and commercially available, including three versions with parameter values of 102B (102.6 billion), 51B (51.8 billion), and 2B (2.1 billion). Compared with Source 1.0, Source 2.0 has improved programming, reasoning, and logic.
- **01.AI - Yi**
In November 2023, 01.AI released the Yi series of models with parameter sizes between 6 and 34 billion and 30 billion tokens of training data.
- **Fire-Flyer Quant - DeepSeek**
DeepSeek, a division of High-Flyer Quant, has released its 67B open-source large model. DeepSeek has open-sourced the 7B and 67B scale models, which contain a base model (base) and an instruction tuning model (chat). No application is required, and it is free for commercial use. At the same time, the project team has also opened nine model checkpoints in the middle of training for download.
- **Ant Group - CodeFuse**
Ant Group has open-sourced CodeFuse-13B and CodeFuse-CodeLlama-34B for CodeLlama, which currently supports a variety of code-related tasks such as code completion, text-to-code, and unit test generation. The open source includes the MFT (Multi-Task Fine-Tuning) framework, a dataset for enhancing the coding capabilities of LLMs, and a deployment framework.

- **Meta Llama 2**
In July 2023, Meta announced the Llama 2 project and disclosed that they had successfully open-sourced three pre-trained models at different scales, which included the 7B, 13B, and 70B parameter versions. These models were trained on a massive 2 trillion token scale during the pre-training phase. In the Supervised Fine-Tuning (SFT) phase, they were fine-tuned with over 100,000 pieces of data to improve their performance on specific tasks. Additionally, Meta made the Llama2-Chat model open-source, which is SFT-optimized based on conversation data. Furthermore, Meta is continuing to open-source the CodeLlama programming language large model.
- **Mixtral 8x7B**
In December 2023, Mixtral open-sourced the Mixture of Experts (MoE) open-source model Mixtral 8x7B, commercially available under the Apache 2.0 license. Mixtral-8x7B is a Mixtrue of Experts consisting of eight networks of experts with 7 billion parameters, a structure that improves the model's efficiency in processing information and reduces operating costs. 
- **Falcon 180B**
Falcon 180B is an open source large language model released by the Technology Innovation Institute (TII). The model has 180 billion parameters and was trained using TII's RefinedWeb dataset.
- **Arabic AI Large Models Jais Open Sourced**
A team of UAE researchers has announced the open-sourcing of the Arabic large model Jais. Jais is a bilingual Arabic-English large language model pre-trained with 13 billion parameters.
- **Microsoft open-sourced visual foundation model Visual ChatGPT**
Microsoft has launched Visual ChatGPT, an open-source project that combines OpenAI's ChatGPT with a series of Visual Foundation Models (VFMs) to enable users to send and receive images during chats. The project aims to extend the functionality of ChatGPT so that it can not only process text but also understand and generate images, thus enabling a multimodal interactive experience.
- **NVIDIA officially open sourced TensorRT-LLM**
NVIDIA has officially released an optimized open-source library called TensorRT-LLM. This library helps to speed up the performance of large language models on AI GPUs such as Hopper. In order to test the performance, NVIDIA compared H100 with TensorRT-LLM-enabled H100, both based on A100. The results showed that in GPT-J 6B inference, the performance of H100 was 4 times better than A100, while the performance of TensorRT-LLM-enabled H100 was 8 times better than A100.
- **Elon Musk drives the efforts of X (formerly Twitter) to open source its recommendation algorithm**
X (Twitter) has released two repositories on GitHub (main repo , mlrepo) that cover much of the Twitter source code including recommendation algorithms, including the mechanisms used to control the tweets users see on the For You timeline.
- **Hugging Face changes its Text Generation Inference (TGI) licence**
Hugging Face has announced that in the latest release of TGI v1.0, its open-source license will change from Apache 2.0 to HFOIL 1.0. HFOIL stands for Hugging Face Optimized Inference License, which is HuggingFace's specifically designed license agreement for optimized inference solutions.
- **Hugging Face has open sourced Rust-based machine learning framework Candle**
Hugging Face recently open-sourced Candle, a novel and small Rust ML framework that runs extremely fast and supports a wide range of powerful models. It provides support for GPUs and has an optimised CPU backend that runs in the browser. Candle also includes several pre-trained models and use cases, such as speech recognition models, generic LLMs, computer vision models, and more.
- **Alibaba has open sourced AnyText**
Alibaba has recently released a multi-language visual text generation and editing model called AnyText. This model allows users to create text that is comparable to that of a professional Photoshop editor. With AnyText, users can customize the location, strength, intensity, and number of text seeds that appear in a picture. 
- **Jina AI launches world's first open source 8K Text embedding model**
Jina AI announced the release of the Jina-embeddings-v2 model, an open source product that supports 8K (8,192 tokens) context lengths and is similar in functionality and performance to OpenAI's text-embedding-ada-002.

### 1.2 Operating Systems and Programming Languages

- **The Long Term Support (LTS) version of Linux kernel now has 2-year maintenance period instead of 6**
The Linux kernel LTS releases were extended to six years in 2017. Recently, a tweak was made to the policy. Jonathan Corbet of Linux Weekly News said it doesn't make sense to maintain old kernels for so long because they're not used much.
- **India's Ministry of Defence develops its own Linux distribution, Maya OS, to fully replace Windows**
India's Ministry of Defence has announced a significant overhaul of its cybersecurity system. It plans to replace the Windows operating system with a Linux distribution called Maya in all its networked computers. The move is in response to the growing threat of malware and ransomware attacks. It aims at promoting independent innovation and reducing dependence on foreign software.
- **Red Hat Announces CentOS 7 and RHEL 7 end of support on 30 June 2024**
Red Hat has recently announced the discontinuation of support for CentOS 7 and RHEL 7. In addition, the complete source code for RHEL will no longer be publicly available. To maintain compatibility and support, downstream distributions of RHEL (such as CentOS, Rocky Linux, AlmaLinux, etc.) will need to recompile and release their versions within 30 days.
<br> However, it is important to note that Red Hat has assured the CentOS community that it will not be going away. Community contributors and CentOS users will still be able to collaborate on open-source Linux distributions that are part of the CentOS Stream project.
- **Google's open-source browser project Chromium announces the use of Rust**
Google has posted a blog post announcing that it will support using third-party Rust libraries from C++ in Chromium, with plans to include Rust code in Chrome binaries by the end of the year. It also said that Rust, a Mozilla-developed programming language that offers security along with high performance, was initially designed to be used for writing browsers, so it's only fitting that open-source operating systems like Chromium rely on the technology.
- **Open-source operating system openKylin 1.0 officially released, already supports Arm, RISC-V**
The latest version of openKylin, version 0.9, now supports Arm and RISC-V. Additionally, the new openKylin 1.0 version comes with 6.1+5.15 dual kernels by default, along with independent selection and upgrade of 20+ operating system core components. The latest version also adds many new features and fixes more than a thousand bugs, improving the overall stability and compatibility of the system to provide users with a better experience.
- **Huawei officially releases HarmonyOS 4**
Huawei officially released the HarmonyOS 4 operating system. The new HarmonyOS 4 is said to have breakthroughs in privacy and security, AI large model capability, and personalized interaction.
- **fit2cloud open sourced 1Panel**
1Panel is a modern, open-source Linux server operation and management panel that provides users with accessible server-building and management resource services.
- **AWS open source specific language Cedar Cedar**
AWS has released Cedar as open source. Cedar is a domain-specific language that enables defining policy access permissions. It is integrated into Amazon Verified Permissions and AWS Verified Access. Cedar can also be integrated into applications through SDKs and language specifications.<br> 
Cedar allows defining access policies separately from the application code, which facilitates writing, analyzing, and auditing the policies independently. Cedar supports both Role-Based Access Control (RBAC) and Attribute-Based Access Control (ABAC).
- **Microsoft releases Guidance language**
Microsoft has introduced a domain-specific language called Guidance, designed to enhance developers' ability to manage contemporary language models. The new framework integrates generation, prompting, and logic control into a unified development process. The programming language enables developers to 'organize generation, prompting and logic control into a continuous flow that matches how the language model processes text.'<br>
It integrates seamlessly with providers such as the Hugging Face model. It combines an intelligent seed-based generation caching system and token healing to optimize prompt boundaries and remove bias in the lexical slicing process.


### 1.3 Hardware Technology and the Internet of Things <span style="color:red">(未审核)</span>
    
- **China supports the construction of human robot open source communities**

    In October 2023, the Ministry of Industry and Informatization of China published the Human Robot Innovation Development Guidelines, which set out to “build open human robotic communities and promote open source foundation capacity-building, strengthen support for focused enterprise open source projects and bring together developers from around the globe to collaborate in innovation”.

- **The University of Stanford publishes an open source robot mobile ALOHA**

    In March 2023, Stanford University released an open source robot mobile ALOHA (a Low-cost Open-source Hardware System), which can perform subtle tasks via remote handling, and by the end of 2023 it will be possible to implement simple mission autonomy through joint training by the end of 2023.

- **Tesla Open Source on Roadster Runner Design and Engineering Details**

    Musk wrote on the social platform that Tesla initially “full open source” for the design and engineering details of the Roadster runway, and published research and development documents accessible to all.

- **openKylin officially joined the RISC-V Foundation**

    The open Kylin community announced its official membership in the RISC-V Foundation as a member of its industry coalition, contributing more to the building of the RISC-V ecosystem, and building operational systems in synergy with the development of the RISC-V architectural soft hardware ecology.

- **The Ari Flat Open Source Base RISC-V Series**

    Horizontal RISC-V series of processors and open series tools and systems software were initiated.This is the first global full-stack open source for series processors and basic software, and will push the RISC-V architecture to mature, helping RISC-V hardware and hardware technologies to accelerate the integration of development and drive innovation landing.

- **AMD Open Source FSR**

    AMD has opened up FidelityFX Super Resolution3 under MIT license to compete with Anglo-DLSS but, unlike DLSS it does not rely on a private CUDA core, but is based on software.

- **BifroMQ** messages under 100th open source flag\*\*

    BifroMQ MQTT Broker Message Intermediary under the BTP Open Source Flag, which is implemented by Java, features "High performance, distribution", BifroMQ using Serverless Structures, seamlessly integrates native multi-tenant support from the BTT network team over many years of technical accumulation, designed to support the building of large-scale Internet connection devices and messaging systems.

### 1.4 Data Infra <span style="color:red">(未审核)</span>

- **DragonflyDB 1.0**

    DragonflyDB is a modern open source memory database compatible with Redis and Memcached API, which is an alternative to both migration without changing any code.In recent days, DragonflyDB officially released version 1.0 and the development team stated that it had supported use in the production environment, Dragonfly 1.0 fully supported Redis for the most common data types and commands as well as snapshot, master copy and high availability features.

- **FerretDB 1.0 officially released**

    FerretDB 1.0 with the name MongoDB open source alternative is officially released, and FerretDB wishes to bring the work load of the MongoDB database back to its source so that the PostgreSQL and other database backends can run MongoDB work loads, keeping the opportunity offered by the MongoDB existing ecology.

- **Apache Doris version 2.0.0**

    Apache Doris 2.0.0 was officially released on August 11, 2023, with over 4,100 optimizations and fixes submitted by more than 275 contributors.In version 2.0.0, Apache Doris received more than 10 times higher in standard Benchmark data sets.

- **Apache SeaTunnel Graduates into Apache Top Level Project**

    This is the first country-led top project in large data integration fields that contribute to ASF.Apache SeaTunnel original named Waterdrop, renamed SeaTunnel in October 2021 and joined the Apache incubator.SeaTunnel is a highly user-friendly and highly performing distributed data integration platform that supports real-time synchronization of volume data.

- **GraphScope of the Ariyun Open Source calculator will be able to use an authoritative list**

    The LDBC SNB Interactivity list for the International Authority-Map Baseline Review publishes the latest results, and the Ariyun Open Source GraphScope computing engine topped and broke the history record of the list with a throughput rate of more than 30,000 QPS for the single node implementation map database searches, twice as high as the previous record keeper.

- **100 Opened from the high-performance search engine Puck**

    The 100th is declared open under the Apache 2.0 protocol from the research search engine Puck, which is the first open source search engine in the country to be applied to superlarge data sets.

- **Byte jumped open source ByConity**

    Byte jump into the Byte House to Community Open Source and publish version 0.1.0 in the Official Officer.

    ByConity is an open source cloud data repository based on the Apache 2.0 license but using a new architecture for storing and calculating separation, supports several key features such as storage separation and elasticity amplification, segregation of tenant resources and strong consistency in data reading, etc.

- **Ali's Open Source Multi-Database Client Chat2DB**

    Chat2DB is an open source multi-database client tool that supports windows, mac local installations, server deployments, web page access.Chat2DB is integrated into AIGB compared to the traditional database client software Navicat and DBeaver and can convert natural languages to SQL, or SQL to natural languages and give research and development staff SQL optimization suggestions.

- **ApeCloud open source KubeBlocks**

    KubeBlocks is an open-source system software for operating and managing data infrastructure on K8s, designed to help developers, SRE, platform engineers deploy and maintain dedicated DBPaaa in the enterprise and support a wide range of public and private cloud environment deployments.KubeBlocks is the only open-source multi-engine data currently captured by CNCF Cloud Native LANDSCAPE.Currently 32 databases are supported, including MySQL, PG, MongoDB, Redis, Kafka, Pulsar, etc.

### 1.5 Cloud Computing and Infrastructure Software <span style="color:red">(未审核)</span>

- **GragGAN Open Source 20 000 Star a day**

    DragGAN is a project developed by Google researchers together with the Max Planck Institute of Informatics and the Massachusetts Institute of Massachusetts in CSAIL Province and is a very intuitive image editing tool that allows users to quickly adjust the location, posture, emotion, size and angle of the body of the photo by controlling the pixel and direction of the image.

- **LLMOps platform Dify.AI code is completely open-source**

    LLMOps Platform Dify.AI declares full open source for line 46,558 and temporarily decides to liberalize the open source protocol from AGPL to Apache 2.0.

- **Huawe's open source cross-end, cross-frame, cross-version enterprise front-end application library OpenTiny, and high-performance service grid Kmesh**

    OpenTiny is a cloud open source web app front-end development suite covering Vue2/Vue3/Angular multi-tech stack, has a theme configuration system/CLI command line and so on.

    The Kmesh high-performance service grid is a new grid of grid performance experience for developers through architecture innovations, the implementation of OS-derived service grid data factor, the sinking of traffic management under OS, and the significant enhancement of access to grid services based on ebpf+programmable nuclear technology.

- **Bracket Smart Cloud Open Source release thousands of Sail SDK version**

    Borders of Smart Clouds officially publish the Python SDK version (thousands of Schar SDK) and have a full open source that businesses and developers can download and use free of charge.

- **Generic Multimedia Processing Framework BMF** for Volcanic Engines\*\*

    The official open source BMF (Babit Multimedia Framework, eight-bit Multimedia Processing Framework) of the Volcanic Engine is a generic multimedia processing framework developed by the Volcanic Engine to provide simple cross-language interfaces and flexible movement and extension.

    Dynamically modulated, dynamically extended, managed, and reprocessed video power and build high-performance multimedia processing links in the form of Graph to help multi-media users move projects into productive environments.

- **Byte Jump Publish and Open Source Rspack**

    Rspack is a Rust language-based Bundler incubated by ByteDance Web Infra team with high performance, compatible webpack ecology, customized strength, etc. Rspack is now supported by Webpack Loader structures.

## 2. Open Source Ecology Chronicle <span style="color:red">(未审核)</span>
    
An interesting phenomenon is that：should be written in business if something good happens in open source circles.And if something bad happens, most of it can be put into the ecology.Of course, it is not only bad things but also good news, as well as national policies that have a profound impact on open-source ecology.

### 2.1 Leading enterprises are laying off open source workforce <span style="color:red">(未审核)</span>
    
From the beginning of January, reports of Google, GitHub and GItLab retrenchments, even companies such as red caps, were being downloaded, followed by major factories in the country and continued disclosures of redundant messages.While this big story focuses primarily on open source ecology and open source situations, it is objectively true that big plants are not specifically designed to reduce open source talent.However, once the downsizing begins, the open-source staff within the enterprise will become more “suspicious” and will be asked what value：you have created for the company?And this question is never easy to get a serious and positive answer!

### 2.2 Prominent figures in the open-source community are facing financial difficulties <span style="color:red">(未审核)</span>

The next news is all the more boasting.The 12,000 people that Google lost were called “Golden 12K,” among them famous open-source bosses.For example,：created Chris DiBona, co-founder of Samba, 61-year-old Jeremy Allison of Google OSPO 19 years ago, "just fired from Google."I am interested if someone needs SMB 1/2/3 protocol or open source experience”.

There are other famous open-source experiences that are even more tragic, let's list the title：

- Open Source Frame NanUI Author Rotate Steel, Project Stopping Development
- Embracing in October, the Internet and struggling to feed itself!Expansion 9 billion downloads of open source projects, behind 9 years
- Given funding shortfalls, the full-time developer has written about：this open source software that may not have a future!》
- “Unleashing Mirage, Distinguished Open Source Project Author “Making Money Online”
- ：“The foundation of free open source software has collapsed”
- Severe funding shortfall, another popular open source project announcing discontinuation of functional development

What is really the “hearts of the heart, the eyes and the tears”.Last year’s opening story, we were also talking about the “dusty of individual heroism.”Today, this trend has become increasingly apparent.

:::info Expert Review
**Defender of the Sword vanad**：is good if it is playing an open source with a playing mind, without taking into account the question of money.If the livelihood problem has not been solved, let us not engage in an open source of physical and mental health and be good when an amateur hoby.Because open sources are not in themselves used to make money.
:::
    
### 2.3 Well-known open source projects are ceasing development one after another <span style="color:red">(未审核)</span>
    
In 2023, there were a number of well-known open source projects, both domestic and foreign, which were declared inactive for different reasons.

Most out of spectrum, the approximate number AetherSX2, the best playStation 2 simulator on Android platform.The developer was only allowed to stop development because of "endless impersonation, complaint, unjustified demands, or even death threats".

The most unbearable is aardio, a programming language focused on the development of desktop software, where the author declared that he would no longer be able to maintain the project because his wife suffers from cancer.

There are also common reasons such as the lack of money and the collapse of open dealers：Touca, libjpeg-turbo;：Peek, wangEditor, lodash;：Peek, which has eliminated old technology from the new era as a result of technological advancement; and a series of old versions that are no longer maintenance.

### 2.4 40 years of Free Software Foundation's rugged journey <span style="color:red">(未审核)</span>
    
On September 27, 1983 Richard Matthew Stallman (acronym RMS) announced the development of a Unix Free Software Operating System (GNU Plan), through which a Free Software Campaign was launched.By 2023, the Free Software Foundation also published an article celebrating 40 years of GNU and free software movements.

FSF Executive Director Zoe Kooyman stated that GNU was not only the most widely used operating system based on free software, but also central to the philosophy that guided the free software movement for 40 years.He also said that we hope that the fortieth anniversary will inspire more hackers to join the GNU and achieve the goal of creating, improving and sharing free software worldwide.

However, also in April 2023, it was reported that the Free Software Foundation (FSF) was dying for almost 40 years.According to the author, “FSF does not attach importance to the dissemination of the free software concept, the development, distribution and promotion of copyleft licences, and the monitoring of the development of the free software movement, which is at the same time diverts resources into other idle works”.

Indeed, we are now talking more about open-source software, not free software.So, is it the “free software movement” that has fulfilled its historic mission, or is it possible to revive it through reform?

### 2.5 Ageing of the open source community <span style="color:red">(未审核)</span>

The ageing of open source communities should be an inescapable phenomenon.Even Linus, which has always been the flame fire, has begun to grow in spleen and “problems of the ageing of the nuclear community”.The problem of ageing in the Postgres community is also more serious, and has been largely developed at age 68.The death of the parent of Vim Bram Moolenaar due to illness, and the death of Thien-Thi Nguyen contributor to the GNU Free Software Project, passed on.How should we view the phenomenon of “ageing”?

In fact, we should also see that more young people join open communities and that they often choose to join newer and more interesting youth projects, rather than old ones.

Maybe we really need to think about：old open source projects that must really be active and constantly released?
    
### 2.6 Some encouraging news on China's open-source efforts <span style="color:red">(未审核)</span>
    
Nor can all be said about bad news. After all, there is much good news in China’s open-source community. In April, there was an official report：, “The number of developers of our open source software broke through 8 million.”

In January 2023, Apache Linkis, Apache Kyuubi, Apache bRPC; in February, Apache EventMesh; in June, Apache SeaTunnel, Apache Kvrocks, graduated officially to the apache Software Foundation top-level project.In February, Jina AI formally donated DocArray to Linux foundations, Paralus formally became the CNF sandbox project, and July Istio formally graduated from CNCF.

OpenKylin formally joined the RISC-V Foundation, China became a Premier member of the First PyTorch Foundation of China, and Gang re-elected member of the Apache Software Foundation in 2023, indicating that we are still actively joining and participating in the international open source ecology and playing an important and continuing role.

In February 2023, following the Apache Local Community in Beijing, Shenzhen, ALC also established a Sician sub-station.At the same time, the Open Source Institute launched the Kaiyuanshe City Community project, which by the end of the year had developed 11 cities, including Beijing, Long Sha, Cheng, Grand Duc, Hangzhou, Nanjing, Guangzhou, Shanghai, Shenzhen, Singapore and Silicon Valley.

In March 2023, following the Open Atomic Open Source Foundation, the second China Open Source Foundation, was officially inaugurated in Chongqing.The following organizations have also been launched: “SigStore Chinese Community,” “Open Source Alliance for Innovative Education,” and three open source projects have been formally donated to the Open Source Foundation.It was to be hoped that more high-quality foundations would be established in the future within the country, based on China and contributing globally.
    
**Open source related General Assembly collections for 2023**

- February
  - Shenzhen：First Open Source Hongmeng Conference
- March
  - Beijing：'s Summit of UPO Summit of the Open Source Management Office
  - Beijing：Dev.Together Developer Ecological Summit
- April
  - ：Moving Cloud General Assembly - Open Source Theme Activity Forum
  - Shanghai：openEuler Developer Day
- May
  - Shanghai：Global Open Source Technology Summit (GOTC)
- June
  - Beijing：Congress of Spirituality — AI Open Source Forum
  - Beijing：Open Atomic Global Open Source Summit
  - Beijing：18th Open Source World Summit Forum
- July
  - Beijing：China Internet Congress - Open Source Supply Chain Forum
  - Taipei：COSCCUP Source Source Jobs
- August：
  - Zhang：World Congress on Artificial Intelligence - Open Source Learning Forum
  - Beijing：CommunityOverCode Asia 2023 Apache Software Foundation Asian Congress
- September
  - Zhang：KubeCon + CloudNativeCon + Open Source Summit
  - Shanghai：GOSIM (Global Open Source Innovation Conference)
  - Zhang：Beach General Assembly - Open Source Forum
  - Beijing：OSCAR Open Source Industry Congress
- October
  - Wuhan：Open Source New Bypass：Day Open Multiplication Summit
  - Changsha：CCC Congress
  - Long Sand：1024 programmer section
  - Chengo：COSCon Eighth Annual Open Source Conference
- December
  - Beijing：OpenInfra Days China 2023 Open Source Infrastructure Developer Day
  - Tria：Open Source Computer System Congress
  - Beijing：Operating System Congress \&openEuler Summit
  - Sinn：Open Conference of Atomic Developers
  - Shanghai：Open Source Industry Ecological Congress

### 2.7 The Impact of national policies on the open source ecosystem <span style="color:red">(未审核)</span>

When it comes to open source ecology, it is necessary to mention that open-source policies developed by various countries and regions have a full impact on open source communities, commerce and ecology.A simple summary can be divided into one of the following expert：

- **Government support policy for open sources** In July 2023, a study found that “Britain’s total value added in science and technology comes from open sources, worth up to £13.59 billion,” and that China has a range of policies from central to local.There are dedicated projects for specific open sources (Shenzhen), targeted funding for specific foundation projects (Beijing), and promotion of integration of open source technologies with specific industries.The extent to which the open source industry and the ecology will be affected in particular will remain to be seen in the coming years.
- **Open source has become a weapon of international competition** Whether it's Github blocking developer contributions from Russian companies, or a U.S. lawmaker, proposing to limit Chinese development in the RISC-V space, and a wide variety of "export-restrictive" policies that have been put in place or attempted to be put in place, make the following Reuters report , which appears imminent："Open source software becomes key link in trade war"!
- There have also been a number of initiatives around **open-source security and the policy dimensions** – whether in the United States, the European Union, or China – to introduce a series of laws and regulations relating to “open-source security” and “AI compliance.”This has also been a mixed source of concern for open communities and the growing attention being given to the security sector by the Government, while unsound policies and regulations may hinder the development of open-source technologies.

</font>
    
## 3. Open Source Governance Chronicle
Open-source governance can be divided into three categories: community governance, project governance, and risk governance. Risk governance encompasses different types of risks such as ethical and social risks, legal compliance risks (including licenses), supply chain risks, security risks, and more. Given the importance of open-source security, we have included a separate chronology of open-source security events in the fifth part of this article.

In 2023, a significant breakthrough in the development of Artificial Intelligence (AI) caused widespread debate among experts worldwide. Whether or not to limit the pace of AI development was discussed. At the same time, major geopolitical powers such as the EU, the US, and China focused on creating legislation to regulate AI. Furthermore, open-source technology played a crucial role in catalyzing the development of AI, leading to efforts to define open-source AI.

During 2023, major open-source foundations and organizations from around the globe held online and offline discussions. They aimed to encourage policymakers and legislators worldwide to work together to face the challenges brought by the new era of AI through open-source cooperation and reject techno-nationalism and geopolitical hostility. Despite their efforts, the fragmented global open-source communities, particularly those from Asia and China, still need to gain significant influence on policymakers. Therefore, more attention and collaboration are necessary to address this issue.

We have given more importance to the crucial events related to open-source AI governance this year. Due to limited space, several project governance events have been included in the community and risk governance categories and will not be listed separately.


### 3.1 Community Governance

#### 3.1.1 Controversies in the Rust community

The Rust community underwent a series of crises and governance changes in 2023. Here are some of the major events and outcomes:

- The Rust programming language team faced internal disagreements and created a new Leadership Council to decentralize authority. External experts were attacked by some core members, causing them to leave and leading to resignations. These conflicts led to the announcement of a new programming language called Crab. Crab's developers wanted more support with Rust's design, aiming to be more flexible, efficient, and faithful to Rust's original intent and philosophy.
- The Rust Foundation's new Trademark Policy sparked community opposition over concerns that it could limit Rust's growth and innovation. The Foundation apologized, acknowledged its shortcomings, and promised to revisit and revise the policy while engaging in more dialogue with the community.
- The management of the Rust community faced issues again recently. The organizers of RustConf removed some scheduled keynote speakers without informing them, which led to an outcry and protests within the community. As a result, some well-known Rust developers and speakers decided to withdraw not only from RustConf, but also from the Rust community as a whole.
- Graydon Hoare, the founder of the Rust language, said in an interview that he was helpless and frustrated by the conflict and division in the Rust community, and that he believed that Rust had deviated from his original vision and goals, and that he was no longer able to control and save Rust, and that he hoped that the community would solve the problem on its own and leave him alone.

While the Rust language went through some community crises and governance changes in 2023, it also published a roadmap for 2024 that focuses on three directions: lowering the barrier to learning, expanding the ecosystem, and improving the development process.

The design team for the Rust language has stated that their goal is to simplify the program so that developers only have to deal with the inherent complexity of their domain and no longer have to deal with the unintended complexity of Rust, and also to give library authors more power and flexibility to meet the needs and innovations of their users.

In addition, some observers believe that the Rust language is evolving toward ease of use as it proves its stability, performance, and productivity in 2021. Rust will likely see explosive growth as the cost of learning and use decreases even further. The focus on security, concurrency, and performance, and the growing adoption of the language as a language designed not only for today's challenges but also for the challenges of the future, suggests that the Rust language will be here to stay, but that community governance will remain a top priority must be addressed.

#### 3.1.2 Controversies in the Red Hat community
Red Hat sparked a storm in the open source world in 2023 involving the source distribution and licensing of its two Linux distributions, RHEL (Red Hat Enterprise Linux) and CentOS (Community Enterprise Operating System). Here are some of the major events and outcomes:

- Red Hat, a popular software company, recently made an announcement that it will no longer share the complete source code of RHEL (Red Hat Enterprise Linux) publicly. Instead, it will only provide patches and updates. Additionally, downstream distributions of RHEL (like CentOS, Rocky Linux, and AlmaLinux) will need to recompile and release their versions within 30 days to maintain compatibility and support for RHEL. This decision has caused controversy among the open-source community. Many believe that Red Hat's actions go against the principles of open-source software and that the company is prioritizing profits over the spirit of open-source. The decision has also created difficulties and pressure for downstream distributions of RHEL.
- Red Hat has responded to this, stating that they have not broken their commitment to open source, but rather to protect the brand and quality of RHEL from some bad behavior and abuse, as well as to encourage more users and developers to use RHEL directly and enjoy the services and support it provides.
- CentOS, as the most extensive downstream distribution of RHEL, has been hit the hardest. Its ecosystem and community are facing a crisis of fragmentation and decline, and some users and developers have turned to other Linux distributions, such as Debian, Ubuntu, Fedora, etc., believing that CentOS has already lost its meaning and value of existence.
- Both Oracle and SUSE took advantage of the opportunity to mock and provoke Red Hat, stating that they would continue to support and maintain RHEL's downstream distributions and even invested heavily in creating their own RHEL offshoots, such as Oracle Linux and SUSE Linux Enterprise Server, in an attempt to capture RHEL's market and users.
- Red Hat has released a statement once again to explain why they are changing their RHEL source code release strategy. According to the statement, the company is making this change to improve the security, stability, and reliability of RHEL. The change will also promote innovation and development of RHEL. Red Hat assures that they still respect and support the open source community and welcomes more collaboration and feedback from it.

### 3.2 Risk Governance

#### 3.2.1 Ethics and social risks
AI technology development and application have triggered several ethical, moral, and societal risk debates and concerns related to human safety, freedom, privacy, and responsibility. The following are some of the significant events and viewpoints:

- **Over 1,000 tech leaders and researchers, including Elon Musk**, have called for artificial intelligence labs to suspend the development of advanced systems, warning in an open letter that AI tools pose significant risks to society and humanity. Conversely, Hongyi Zhou, CEO of 360, believes that not developing AI is the biggest insecurity. According to him, AI can help humans solve many problems, and its use can be regulated through laws and regulations.
- **A 22-word statement signed by nearly 400 experts and scholars in the field of AI**, including Geoffrey Hinton, the godfather of AI, Sam Altman, CEO of OpenAI, and Ilya Sutskever, its Chief Scientist, warns that AI could extinguish the human race! It states: "Mitigating the risk of extinction from AI should be a global priority alongside other societal-scale risks such as pandemics and nuclear war".
- **In July 2023, many open-source foundations and organizations from around the world held an international conference in Geneva** with the aim of exploring the relationship between AI and open-source, including the challenges and opportunities involved. The conference concluded that open source is essential in promoting AI innovation and cooperation, and is an effective means of ensuring AI ethics and social responsibility. Many experts from around the globe pointed out that open source is an inevitable trend in the development of AI. They also highlighted that open source makes AI research and application more transparent, fair, and credible. It allows more people to participate and contribute to the development of AI, preventing monopolization and abuse of AI.
- **Three Turing Award winners in the AI field - Andrew Ng, Geoffrey Hinton, and Yoshua Bengio - engaged in a lively debate on social media**. Their discussion focused on the U.S. government's restrictions and bans on AI technology. Andrew Ng criticized the U.S. bans, stating that they hinder the open exchange of AI and are detrimental to AI development and innovation. However, Hinton and Bengio argued that the U.S. bans are necessary controls on AI for security and ethical reasons.

The emergence and utilization of AI technology reflect the diverse ideologies and values worldwide, and their influence on the ongoing humanitarian crisis. AI is not merely a technological issue, but also a political, economic, and social one that necessitates international consensus and cooperation for the creation of sustainable and equitable AI development.

#### 3.2.2 AI Laws, Regulations and Policy Documents are emerging globally
In 2023, several laws, regulations, and policy documents related to AI were issued on a global scale. These included: 
- The Interim Measures for the Administration of Generative Artificial Intelligence Services were jointly announced by seven Chinese ministries and commissions, including China's National Internet Information Office.
- The Global Initiative on Artificial Intelligence Governance was issued by the Office of the Central Committee of the Communist Party of China's Committee on Cybersecurity and Informatization.
- The Executive Order on Safe, Reliable, and Trustworthy AI issued by the U.S. White House.
- The European Parliament, the EU member states, and the European Commission agreed upon the Artificial Intelligence Act.
- The Bletchley Declaration is an international declaration signed by representatives of the governments of 28 countries and the EU.

The documents of China's Global AI Governance Initiative and the European Union's Artificial Intelligence Act reflect the importance of promoting and protecting open source AI technology. For instance, China's initiative encourages the world to work together towards the healthy development of AI, sharing the knowledge and open sourcing AI technology. The EU's AI Act specifies that it does not apply to AI components provided under free and open source licenses unless they are part of a general base model or prohibited AI practices, or subject to transparency obligations as part of an AI system.

#### 3.2.3 Global open-source organizations are addressing new AI governance challenges
In June 2023, the Open Source Initiative (OSI) initiated the Defining Open Source AI campaign, which included online and offline global discussions and events to address the challenges of open-source AI governance. During the campaign, Kaiyuanshe actively participated in the mailing list discussions and organized the translation of the webinar series. The draft document of the Definition of Open Source AI, which has been published, consists of a preamble, a definition of Open Source AI, and a list of evaluation licenses. The document focuses on authorizing the use, study, modification, and sharing of AI systems.

The Apache Software Foundation published Generative AI Guidelines for Contributors in June 2023. The guidelines help contributors who use AI-generated code, documents, and images for ASF projects. They recommend disclosing the AI-generated part of contributions and labeling it as "Generated-by: ". The 

China Academy of Information and Communications Technology (CAICT) released a report titled "Compilation of Trusted Open Source Large Model Cases (Phase I)" in December 2023. The report provides a comprehensive overview of China's open-source large model industry, including technical aspects, application scenarios, business models, governance, and development trends. It serves as a reference guide for developing China's large model industry and analyzes the technology ecology of open-source large models and the industry chain.

#### 3.2.4 Open-source AI large models call for new types of licenses
Open source is becoming mainstream for AI large models, but traditional licenses can't meet their unique needs. New licenses are being explored.

The Open Source Initiative declared Meta's LLaMa license not open source due to commercial use limitations and purpose of use restrictions. Falcon-40B was also challenged for using a custom license with special restrictions and had to change to Apache 2.0. Hugging Face changed TGI's license from Apache 2.0 to HFOIL due to restrictions on selling hosted or managed services on TGI.

By 2023, Hugging Face will have almost half a million models available with different licenses, including Apache 2.0, MIT, and OpenRAIL. The OpenRAIL license is an upgrade from RAIL and has behavioral restrictions. It includes licenses for source code, applications, models, and data: OpenRAIL-S, OpenRAIL-A, OpenRAIL-M, and OpenRAIL-D.

China's domestic standards and research institutions are actively promoting innovative AI licensing practices. In May 2023, the China Academy of Information and Communications Technology (CAICT) jointly compiled and released the "Zhiyuan Open AI Model License Version 1." This license regulates the use of models (including their derivatives and supporting materials) but does not apply to the training data of the models. In August 2023, the Shanghai Jiao Tong University Intelligent Court Research Institute, along with the Artificial Intelligence Research Institute and Shanghai Magnolia Open Source and Open Research Institute, organized a workshop on designing the framework of the Mulan-Magnolia Open Data License 2.0. The license's function is to provide an open license for AI data. In December 2023, the OpenAtom Open Source Foundation and the Magnolia Open Source Community, the OpenI Qizhi Community, and other communities jointly developed the Mulan-Qizhi Model License (Beta). The license applies to models obtained through algorithmic training and supplementary materials, including model structure, parameters, weights, etc. However, it excludes the training models' algorithms and algorithmic source code.
> **Commentary**: 
> Wei Jianfan: I believe that these disputes will soon cease to exist, and as long as the law is clear, all similar problems will be solved.

#### 3.2.5 The development of China's open-source field standard is gaining momentum.
China supports open-source standards and will develop standards for open-source terminology, licenses, interoperability, project maturity, community operation, governance, and supply chain management for open-source software.

A new national standard for evaluating the open source code security of software products was drafted in April 2023 by the National Information Security Standardization Technical Committee, led by the China Academy of Information and Communications Technology. It is now open for public comment.

In July 2023, the Chinese Electronics Industry Standardization Technology Association (CESTA) approved three group standards related to open-source technology. These standards provide guidelines for open-source governance and project evaluation. They include T/CESA 1269-2023 Information Technology Open Source Terminology and Overview, T/CESA 1270.1-2023 Information Technology Open Source Governance Part 1: Overall Framework, and T/CESA 1270.4-2023 Information Technology Open Source Governance Part 4: Project Evaluation Model. The Chinese Research Institute of Electronic Technology (CRIET) released these standards. T/CESA 1270.4-2023 Information Technology Open Source Governance Part 4: Project Evaluation Model and three other open-source group standards have been approved and published for use.

In September 2023, the Chinese Academy for Electronic Technology Standardization formally approved four open-source standards. The China Electronics Industry Standardization Technology Association examined and approved these standards. The agreed standards are T/CESA 1270.2-2023 Information Technology Open Source Governance Part 2: Enterprise Governance Assessment Model, T/CESA 1270.3-2023 Information Technology Open Source Governance Part 3: Community Governance Framework, T/CESA 1270.5-2023 Information Technology Open Source Governance Part 5: Open Source Contributor Assessment Model, and T/CESA 1291-2023 Information Technology Open Source Metadata General Requirements. The Community Governance Framework, Open Source Contributor Assessment Model, and Information Technology Open Source Metadata Requirements are among the four open-source standards that have been formally approved and released.

In October 2023, two open-source software group standards were approved and released. These standards were titled "Open Source Software Governance Evaluation Methods Part 3: Maturity Models" and "Open Source Software Governance Evaluation Methods Part 5: Governance Tools and Platforms". The China Academy of Information and Communications Research (CAICR) led the development of these standards, and they were reviewed and supported by the China Association for Communications Standardization (CAICS).

## 4. Open Source Security Chronicle
In today's digital age, software has become an essential element that supports the normal functioning of our society. However, as the software supply chain becomes more complex, so do the security issues. The Log4Shell vulnerability recently brought open-source security into the spotlight. Despite 2022 being touted as the "Year of Supply Chain Security," the vulnerability is still widespread, and the rate of adoption of fixes is low. As a result, the frequency of attacks in the software supply chain has skyrocketed. The broad adoption of open-source code has turned supply chain security into an existential issue. Log4Shell has made headlines as it revealed the security risks present in the open-source community. Moreover, other projects that are heavily reliant on open-source in the ecosystem may have a more extensive reach and more severe consequences than Log4Shell. Supply chain attacks are on a sharp upward trend, averaging 742% annual growth since 2019. Therefore, we need to focus on improving the security of open-source software.

### 4.1 Latest trends and challenges
An analysis of the latest trends and challenges in open-source security, including the following:
- **Malware as a Service**: Hackers use open source code and tools to develop and distribute malware, creating a massive black market that threatens the security of the open source ecosystem.
- **Human Errors**: Open-source projects are vulnerable to attacks due to human errors, such as ignoring security updates, using weak passwords, and leaking sensitive information by developers and maintainers working with open-source code.
- **Supply Chain Attacks**: occur when hackers inject malicious code into open-source projects by manipulating repositories, dependency packages, or update channels, thereby compromising the reliability and trust of these projects.
- **Legal Risks**: Open source projects may face legal risks in complying with license agreements, dealing with copyright disputes, responding to policy changes, etc., which must be identified and resolved promptly.
- **Security Standards**: Open-source communities and organizations are developing and promoting some security standards and best practices, such as SLSA, OpenSSF, CII, etc., to improve the quality and security of open-source code.
- **Security Tools**: Open source projects can utilize some open source or commercial security tools, such as Snyk, Dependabot, CodeQL, etc., to detect and fix security vulnerabilities and improve security protection.
- **Security Education**: Open source projects need to strengthen security education and training, improve the security awareness and skills of developers and maintainers, establish a security culture and process, and prevent security risks.
- **Security Cooperation**: Open source projects must strengthen security cooperation with other open source projects, organizations, enterprises, governments, etc., share security information and resources, form a security community, and jointly address security threats.
- **Security Outlook**: The security landscape for open-source projects presents a mixed prospect. While the prevalence of increasingly intricate and severe security challenges is noteworthy, open-source projects are fortified by a sturdy and dynamic security force.

### 4.2 Legal liability of open source security
There is an ongoing debate concerning the legal liabilities of open-source software regarding security. The prevailing argument and accompanying legislation state that the authors of open-source software bear responsibility for any vulnerabilities detected in the code. Despite being offered free of charge, the authors are expected to guarantee the quality and security of their software. Vulnerabilities can cause significant harm, such as the compromise of user data and system attacks, making it imperative for authors to fix identified weaknesses and inform users promptly and swiftly. As such, the current trend in global legislation is to hold open-source legally accountable for cybersecurity.

- In **China**, providers of network products and services are forbidden from developing malicious programs. They must take immediate corrective action, promptly notify users according to regulations, and report to the relevant authorities if security flaws, loopholes, or risks are identified in their network products and services. Furthermore, network product and service providers must maintain ongoing security for their products and services. They are not permitted to terminate the provision of security maintenance within the period specified or agreed upon by the parties. If a network product or service can collect user information, its provider must obtain explicit consent and communicate this to users. Moreover, if personal information is involved, the provider must comply with the relevant laws and administrative regulations on personal information protection.
- **The EU Cyber Resilience Act (CRA)** aims to strengthen the cybersecurity of digital products in the EU by consolidating the existing cybersecurity regulatory framework. The Act imposes many cybersecurity requirements on digital products, including software. The Act is closely linked to the Highly Common Cybersecurity Directive (NIS 2 Directive), the Cybersecurity Act, the Artificial Intelligence Act, and the General Data Protection Regulation (GDPR). It could become one of the most critical EU cybersecurity laws.

### 4.3 Some important open source security incidents in 2023

#### 4.3.1 Log4j vulnerability resurrection
LLog4j is a tool for developers to track their programs. In Dec. 2020, a severe issue let hackers control computers using Log4j. Alibaba and Amazon were affected. The Log4j team quickly fixed it in Jan. 2021 with Log4j 2.15.0.

However, Log4j 2.15.0 has a new vulnerability, CVE-2021-44228. Attackers can exploit a Java problem by sending specific log messages. Log4j 2.16.0 turns off the Java feature in log messages to address this. Users must upgrade now and turn off unused logging. Use firewalls and intrusion detection to block malicious traffic. 

#### 4.3.2 Linux malware growth rate soars to 50%
Linux malware surged 50% to 1.9 million threats in 2022, with Trojans, botnets, ransomware and mining software used to steal data, control devices, and extort money. Infections spread through web services, email, web pages, and mobile devices exploiting vulnerabilities, weak passwords and social engineering. To protect against Linux malware, regularly update systems and software, use strong passwords and two-factor authentication, install reliable anti-virus software, and avoid opening suspicious links and attachments.

#### 4.3.3 New threats to the npm supply chain: "manifest confusion"
Manifest Confusion is a security problem that affects the npm registration process. Attackers exploit this vulnerability to hide harmful code or dependencies by providing incorrect manifest information that does not match the contents of a tarball package. This security issue can affect millions of npm users and projects, potentially leading to the theft of sensitive information, execution of remote commands, spreading malware, and more. Developers and maintainers can prevent this vulnerability by using npm shrinkwrap or package-lock.json to lock down dependency versions, using npm audit, avoiding installing packages from untrusted sources or mirrors, and checking that the manifest information matches the contents of the tarball package before releasing it.

#### 4.3.4 Electron's shocking Level 10 vulnerability!
Electron is a framework for cross-platform desktop apps. It has a significant vulnerability that lets hackers use a bad link to run harmful code. Apple and Google warned about this, but many apps have not been updated. The vulnerability is caused by an old version of Chromium. To fix it, Electron needs to use a newer version of Chromium. The Electron team has already released a new version that fixes the problem. It's important for developers to keep their software up-to-date and secure. Finally, developers should always check their code for vulnerabilities.

#### 4.3.5 Google awards $12 million for solving 2,900 vulnerabilities
Google's Vulnerability Reward Program (VRP) paid $12M in bonuses to security researchers from 68 countries who found 2,900 vulnerabilities in 2022. The highest reward for a single vulnerability was $605,000. The VRP now covers Google Nest and Fitbit.

#### 4.3.6 GitHub adds SBOM export feature to make it easier to comply with security requirements
GitHub's new feature helps developers quickly create and export software build bills of materials (SBOMs) to enhance security and transparency. SBOM documents contain information about the software components and dependencies used in the codebase. The resulting SBOM can be accessed from GitHub's Security Tab and exported as SPDX or CycloneDX-format files.

#### 4.3.7 OpenAI, Google, Microsoft and others create $10 million AI security fund
Tech companies and research organizations, including OpenAI, Google, and Microsoft, have created a $10 million fund for AI security and ethics research. The goal is to promote responsible and trustworthy AI development, prevent risks, and encourage more participation. The Fund will be managed by an independent committee, which will select the most outstanding projects for funding.

In brief, open-source software necessitates enhanced security risk governance mechanisms, including quality standards, security audits, vulnerability rewards, and shared responsibility. Similarly, open-source software necessitates more significant investment and support, including financial resources, workforce, and community engagement. The future of open-source software development relies on our response to the current situation and our ability to establish a more sustainable and secure open-source ecosystem.
    
## 5. Open Source Commercialization Chronicle <span style="color:red">(未审核)</span>

### 5.1 Early stage financing activities <span style="color:red">(未审核)</span>
    
- **Open source database management tool DBeaver earned $6 million in Gold Wheel funds**

    DBeaver 2013 Open Source, based on Java development, can operate on various operating systems and is a free open source common database management and development tool.Its founders set up commercialized companies in 2017 to provide enterprise-level support and develop business versions.Currently DBeaver already has 8 million users, with 5,000 fee-paying clients, including IBM, Samsung, and Moody’s.

- **Open Source Large Model Company Gogether received 20 million US dollars in finance**

    Gogether expects to get $20 million in seed wheel financing by providing open ecosystems with cross-computing and first-class basic models.Together is building a cloud platform for running, training, and fine-tuning source models.RedPajama is one of Together's first projects to nurture an open source generation model Gogether that is now open with 1.2 trillion token training data sets, and Together is allowed to commercialize on the open source platform.

- _Open source AI and Data Streaming Union AI received $1.91 million in A Wheel financing_\*

    Union AI provides Flyte hosting services (Organization ETL, Machine Learning Workflow), also builds Pandera (Data Test Framework) and Union ML (above Flyte, which can help teams build and deploy models using existing tool-based) and launched the Union Cloud this year with $19.1 million in NEA rotation.

- **Open source DB for AI MindDB receives $2500 million in seed wheel financing**

    MindsDB is defined in the DB For AI scenario, which uses AI-Table as a virtual table in the database, connects data and models that allow users to model directly in the database, save the onerous steps of data processing, machine learning models, etc. and accelerates the landing of AI applications.MindDB received multiple rounds of funding in 2023, totalling nearly $50 million.

- **The Open Source LLM firm Misal AI received multiple rounds of financing to join Licorne**

    The recent release of the open source Moe model Mixtral 8X7B, founded by Meta and Google scientists, has raised great concerns.Misal AI also completed multiple rounds of financing last year, earning $415 million in the latest round A funding and currently valued at more than $2 billion.

- **Model Continuous Test Certification Tool Deepchecks Gold 1400 million Gold Wheel Financing**

    The Israeli company Deepchecks is located in the ML continuing testing field and allows customers to reuse and customize components to fully test ML models and data sets.Deepchecks launched an open source ML test tool in 2020 and launched Deepchecks Hub, a commercial version earlier this year.

    To date, open source Deepchecks have been downloaded more than 500,000 times, with users including AWS, Booking.com and Wix.Deepchecks announced $1400 million in Angel Wheel.

- **Open Source Component Supply Chain Secure Platform Endor Labs Earned $70 million A Wheel financing**

    Ender is positioned to help enterprises monitor the security of their development pipelines, including touchable and available risks, manage developers' access to the code and follow the confidentiality of hard codes in their repositories.Recently they received $7 million A round funding from Lighted Venture Partners

- **AutoGPT completes $1.2 million**

    AutoGPT builds a multi-function intelligent body using language models such as GPT-4 and GPT-3.5 that can perform tasks independently and continuously improve performance.The project is online for more than 50 days, with 13.1w star, 267 million fork, one of the fastest-growing projects in GitHub's history.

### 5.2 Mid to late stage financing activities <span style="color:red">(未审核)</span>
    

- **UK MLOps Seldon earned $20 million in $B wheel financing**

    Seldon was established in 2014 to address the issues of deployment, monitoring, management and interpretation of AI Model at the production level.2020 A Revolving Finance to date, Seldon's open-source product installation has increased by YoY 400%.

- **Temporary receives $75 million in finance**

    A new temporary company based on the Uber Open Source distributed task preparation and dispatch engine Cadence receives $7500 million in new funding rounds, valued at $1.4 billion.

- **SAST/SCA Open Source Development Vendor Semgrep obtains C Wheel Fund**

    Semgrep is cut from the SAST field. It has a SAST engine. Users can integrate it with their CICD processes and code hosting platforms such as Github, Gitlab and use Semgrep built-in and custom rules.Semgrep opened up the product in 2020, and now has 2 million new users, with its 2022 earning 7.5-fold increase compared to 2021.

- **France AI Research Lab receives $330 million in investment for all results open sources**

    The French billionaire and CEO Xavier Niel of Iliad launched an AI research laboratory called Kyutai in Paris.It is a not-for-profit institution supported by private funds and focused on research in the field of artificial general intelligence.Laboratories currently raise almost €300 million in funding and Kyutai focuses on basic AI model research supported by Scaleway top-level computing resources from Nvidia H100 GPU

- **Replicate Open Source Platform receives $4000 million in B wheel financing**

    Business Replicate of Open Source Machine Learning Model Platform, recently announced successful completion of round B financing by Andreessen Horowitz, totalling $400,000, will continue to strengthen the Open Source Machine Learning Model platform.

### 5.3 Mergers and acquisitions (M&A) <span style="color:red">(未审核)</span>
    
- **AMD Acquisition of Open Source AI Software Nod.ai**

    AMD announced on the official network that the final protocol would take Nod.ai, Nod.ai would speed up the deployment of optimized artificial intelligence solutions on AMD high-performance platforms, and strengthen AMD open source software strategies.

- **Snowflake intends to acquire Ponder enhanced data cloud Python**

    Ponder is a leading company that connects the epidemiological data science library to the location of the data and maintains the widely used Open Source Modin for expanded Pandas operations.In order to better serve Python data practitioners, Snowflake announced his intention to purchase Ponders.

- **Cisco announced plans to acquire Isovalent** the Innocenti Network Security Initiative\*\*

    Isovalent is committed to the development of eBPF and Cilium two key open-source technologies that can provide insight into operating systems and cloud native applications.Isovalent plays an important role in the Cloud Computing Foundation (CNCF) and the eBPF Foundation.Sustained community support is essential to sustain the dynamic development of these open source projects.

## 6. Open Source Education Chronicle <span style="color:red">(未审核)</span>

This year, China added a special “open-source education” to the highlights of the annual open source report. There are some differences in the definition of open source education in different organizational types. In this chapter, we would like to define open source education as **：using open source software and open educational resources to support educational objectives.This includes the use of open-source software tools, teaching materials and teaching resources, as well as the promotion of knowledge sharing and collaboration.One of the goals of open source education is to provide more equitable and open access to educational resources of high quality.**

In the open source education model, educational resources such as curricula, course content, software tools and so forth are accessible and can be used, adapted and shared by all.This model helps to build students' innovative thinking, collaborative skills and practical problem-solving.Through their participation in open source projects, students have access to the latest technologies and tools of industry to learn about the practical processes of software development and can also contribute to open source communities.

At the same time, as the author of the report, “Open Source Education” is not a stranger to the Open Source Society, and since its inception in 202014, it has actively explored the interface between open sources and education. Before formally presenting the profile of open source education in 2023, we look back at the work of the Open Source Institute in：

- In 2014, the Open Source Society launched China’s first open source series of campuses – the “Open Source Wales”;
- In 2020, the Open Source Education Group and the Higher School Cooperation Group were set up under the ExCom to focus on open source education;
- In 2020, the Third Annual Open Source Conference (COSCon'18) organized by the Open Source Society produced China's first “Open Source Education Sub-Forum”;
- In 2019, the Open Source Institute together with Ciudad Juárez Teacher University set up the first “Open Source Education Fund” in China.
- In 2020, the Open Source Institute recorded a series of Open Source Training Camps designed to provide introductory training in open source education;
- In 2021, at the Sixth Annual Open Source Conference in China (COSCon'21), the Open Source Society invited six guests to share open source education, and for the first time invited students of higher education to share issues related to open source education;
- In 2022, the Open Source Institute was actively exploring the direction of open source education and training, such as specific training in enterprises;
- In 2023, at the 8th Annual Open Source Conference in China (COSCon'23), the Open Source Education for Young People Sub-Forum was launched, for the first time, inviting young students from primary and secondary schools to share open-source perspectives.

In the light of the evolution of these open source societies in their “open source education”, the integration of open sources and education has been deepening, especially among those who have been attending open source education, from open source organizations to institutions of higher education, to primary and secondary schools and to a wider group of employed persons.

However, there is still a shortage of eligible open-source talent both at home and abroad. According to the tenth Annual Open Source Jobs Report, published by the Linux Foundation, the vast majority of employers (93%) have indicated that it is difficult to find a sufficient pool of open-source skilled professionals and that the situation has not eased. There are plans to increase recruitment of open-source talent over the next six months, and 73% of open-source professionals have indicated that they are easily able to find new jobs and continue open source ventures.

The shortage of open source talent has led to an increased global focus on open source education. China is also actively promoting open source education by participating in open source communities, appealing for open source projects, establishing open source education systems, and developing open-source capacity assessment criteria to promote open source ecosystems and human development.Through these initiatives, school students and post-employment groups can gain a deeper understanding of open-source software concepts in the learning process, promote the integration of theory and practice, improve the quality of education and meet the needs of society for innovative talent.Let's go back to 2023 China’s Open Source Education History：

### 6.1 Open-source education has been thriving with interactive practices, project-based learning, and innovation competitions <span style="color:red">(未审核)</span>

In 2023, open source education activities in China increased markedly, attracting a large number of students and supported by a number of prominent institutions.Below are some of the main practice activities：

- **Open Source Summer (OSPP)**：is a summer event guided by the Middle School Software to encourage students to participate in open-source software development.In 2023, 3,475 students from 592 higher schools were registered, 504 students were selected successfully and 1,236 PRs.
- **GitLink does have an Open Source Summer Camp (GLCC)**：hosted by the Chinese Computer Society, which involved 341 students from 139 higher schools in 2023 and resulted in 80 topics being reviewed in the medium term.
- **Sixth China Software Open Source Innovation Match**：has multiple competition channels under the guidance of the Information Science Department of the Natural Science Foundation and hosted by the CNF and focused on the “card neck” software field and front-line technology.
- **The Twelfth National Open Source Software Development Match**：was guided by the China Software Industry Association, the Open Atomic Open Source Foundation, the Open Source Development Committee of the Chinese Computer Society, and the China Open Source Software Promotion Alliance, which attracted 345 party entries from 60+ higher schools and 20 team finals.
- **2023 Open Atomic Open Source**：is sponsored by the Ministry of Industry and Informatization, the People's Government of Jiangsu Province and the People's Government of Hunan Province, and aims to fully exploit the ecological upstream and downstream synergies of the industrial chain, based on the principle of shared sources and co-management of the open source system.
- **The first Chinese Postgraduate System Open Source Innovation Contest**：was hosted by the Chinese Postgraduate Innovation Practices Series and focused on open source innovation in the operating system domain.

In addition, there are **2023 open source and information consumption competitions for enterprises - the Fourth Industry APP and the Information Consumption** - sponsored by the Ministry of Industry and Communications etc. - which help to promote open sources of education for people in the workplace.

These activities have not only increased the technical capacity of students but have also contributed significantly to the spread of open source culture and the activity of open source communities.
    
### 6.2 Domestic open-source software & hardware education theory foundation is forming <span style="color:red">(未审核)</span>
    
In 2023, China made remarkable progress in the field of open-source education not only at the practical level, but also at a growing theoretical base.Higher education teachers and open-source experts have begun to place greater emphasis on research into open-source education theories, and have published representative articles at different levels and directions.These studies provide case and theoretical analysis of open source education, demonstrating the potential of open source education to apply in higher and K12 education.

**At the higher education level**：Open source education is seen as an innovative teaching model that helps students learn software and hardware development skills.For example, teachers at higher schools such as Beijing University, Warsaw Teacher Training University and Shanghai Foreign Trade University have studied the application and value of open-source education in the teaching of their respective disciplines.

**In the K12 education phase**：Open source education is usually combined with STEM, STEAM, robot/drone education, and education for creators, especially through open source hardware.For example, teachers in educational institutions such as the Melchian secondary school in the city of Jujuy and the Luang Sacha primary school in Nanjing have explored the use of open source hardware in project-style teaching.

In addition, the Education and Technical Equipment Centre of the Shanghai Commission on Education held a seminar on the development of resources for education drone and open source hardware courses, which showcased the use of open source hardware in primary and secondary education.The Open Source Robot Games at the Eleventh Congress on Primary and Secondary Education also showcased cases and new trends in the creation of technical education in primary and secondary schools.

These activities and studies show that future outreach of open source education in higher education and in K12 education will differ, but both will tend to open up basic education and open source software and hardware development.Open source education not only helps to improve students' technical skills but also promotes innovative thinking and teamwork and contributes to the pluralistic development of the Chinese education system.

Articles exploring the combination of open and higher education are：

- The Beijing University School of Software and Microelectronics, Wong Qi, von Wizhe, Exploring the Twin-Track Teaching Model in the Confluence of the Profession - An example of the Beijing University Course on the Basis and Practice of Open Source Software Development”
- Zhao Zhao University, The Future of Open Source Education in Digital Perspectives in Open Source Science and Engineering, Faculty of Data Sciences and Engineering, Warden Teacher Training University
- Shanghai Foreign Economic and Trade University Changfong “The value and significance of the introduction of open-source education in higher schools”
- Yellow Big Guides at the Faculty of Computing and Communications Engineering, Changsha Polytechnic University, Studies in Software Engineering Courses Integrating Thinking and Example of Open Source Software
- The New Rural School of Medicine and Medicine at the School of Intelligence, Wang Xiaopingan, Dindan and Bango: Building a new blockchain in medical mathematics from an open-source educational perspective in higher schools.
- Nanjing University of Post and Telecommunications, Taurocho, Wang King, and Gwei “Creative Software Talent with Open Source Ecoculture”.

Articles exploring open source education and K12 education combinations with：

- Therapy for Open Source Hardware Project in the Education Concept, Therapy - The Case for Creative Light Decorations
- Rangaman Elementary School, Nanjing
- Research on the Open Source of Information Technology Education Hardware Channel, Changelin, Yao Ming, published in the journal Education and Equipment Research
- Xi Jun, Fuxing Senior High School, Shanghai："Creators and Open Source Hardware Breathe New Life into Education".

### 6.3 Open source education forums bring together communities <span style="color:red">(未审核)</span>
    
In 2023, open source education showed a marked upward trend in China, as evidenced by the number and frequency of conferences devoted to open source education.These conferences have not only demonstrated the impact of open-source education, but have also facilitated in-depth exchanges and cooperation between the educational community and the open source community.

Some prominent conferences and forums include：

- **2023 GAIDC Global Champions Congress**：at this international conference of developers, the Open Source Technology Forum showcased applications and development from an open source worldwide.
- **The second China Open Source Education Seminar (SOSSEC-2) and the third China Open Source Education Seminar (SOSEC-3)**：, held in Guangzhou and Shanghai, respectively, focused on the current state of development and future trends in open source education in China.
- **National Seminar on Innovative Education for New Business Sectors**：, held in Shanghai, explored open source applications in the field of education, particularly integration in business education.
- **The Fourth Chinese Congress on Computer Education**：as part of the first Forum on Open Source Education for Computers, emphasized the importance of open sources in computer education.
- **2023 Guangzhou Village Forum, the World Open Source Innovation Development Forum**：discussed the role of open source education in scientific research under the theme “Open source education in an open science context”.
- **GOTC 2023**：Open Source Education and Talent Development Summit of Linux Foundation, highlighting the key role of open source technology in talent development.
- **2023 Open Atomic Energy Global Open Summit**：Open Source Education and Talents Forum was successfully convened, giving further impetus to discussions and practices on open source education at the global level.
- **COSCon'23 8th Annual Open Source Conference in China**：Open Source Education for Youth, inviting young students in OpenTeen primary and secondary schools to share relevant experiences of open source practices.

These events and forums have not only raised the profile of open-source education in academia and industry, but have also provided a platform for exchange among educators, students and members of open-source communities and facilitated the sharing of open-source educational resources and the dissemination of best practices.With the rise of open source educational forums, the combination of open sources and education is gradually becoming a new trend in educational innovation and talent development.

### 6.4 Open source talent training and certification are growing <span style="color:red">(未审核)</span>
    
In 2023, an important development milestone was reached in the area of open-source education in China, namely, the launching of the Code of Requirements and Evaluation of Open Source Human Capacity.The development of this standard, led by the Ministry of Industry and Informatization Centre in conjunction with the Open Source Foundation, was attended by 36 participating experts from the Beijing University of Aeronautics and Astronautics, Beijing Polytechnic University, Warden Teacher University, Huahua, Baido, Tencent, Mini-Mei and others, and marked the formal entry of open source education into the National Talent Strategy system.The development of the standards is important for the development of open source talent in China, which will help to promote the high quality development of open source software and technology and establish a set of scientifically sound and industry-recognized standards of human capacity requirements through research and analysis and aggregation.

In addition, open-source teacher training has become an important exploratory direction.For example, the Phongsha City Promotion of Software and Information Technology Services provides teacher-training activities in OpenHarmony Province aimed at deepening the application and understanding of OpenHarmony among teachers in higher education and improving the ability to build a good ecology based on OpenHarmony development techniques and delivery capabilities.

These initiatives and developments indicate that China is actively developing a standard system of open source talent development and certification, which will not only help to improve the professional capacity of open source talent, but will also promote the widespread use of open source technologies and innovative development in the field of education.As the open source education system evolves, it can be expected that more high-quality open source talent will emerge in the future, contributing to open source communities in China and around the world.

### 6.5 Enterprises, higher education and research institutes' new collaboration model <span style="color:red">(未审核)</span>
    
In 2023, Chinese enterprises increased significantly in the area of open source education, and cooperation with higher education has become more open and deepened.Such cooperation usually involves the introduction of practical open source projects into the educational environment, allowing students to participate in high-quality open source projects rather than undertaking basic operational work.Below are typical cases of corporate collaboration with higher education：

- **Answer Project**：has been selected as a integration practice project in Ambienta Norte, allowing students to participate in actual open source projects.
- **CloudWeGo Project**：The project has been integrated into the Norden Graduate Course to enable students to participate in the Open Source Project of the Enterprise; it also works with the University of Nanjing and Zhejiang to promote cooperation and open source development.
- **openKylin**：set up a high school station at Tianjin University of Science and Technology, focusing on open source development.
- **PingCAP**：provides a full experiment in engineering practice in cooperation with the China Database Summer School, which was donated by PingCAP for three years; and a joint PhD development cooperation agreement with the Warden Teacher University aimed at promoting advanced skills development in key software.
- **OceanBase**：, in collaboration with the Teacher Training University of China to address technical challenges, leads the distributed database on research and innovation and open source development.
- **StoneDB**：completes the first internship course, involving a large number of prominent higher education students and focusing on the development of open source databases.
- **Tent**：supports open source development through the Open Atomic School Source Project, and the 2023 Rhino Rhino Bird Open Source Program was launched to help develop open-source talent in higher schools.
- **Bridging the Divide**：jointly with the Beijing Polytechnic University, an Open Source Dividend Talks of Excellence in cooperation with a number of schools.
- **outreach information** The Yartha Valley Secondary School project with the participation of the Spirit Valley under：was selected for the Year 2023 Good Case for Smart Education.
- **Soft International**：, in cooperation with Beijing Polytechnic University, opened the first Open Source Divide Talks at the IT Innovation Institute.
- **Ending the divide**：collaborates with the University of the South East to nurture the open-source talent of the higher schools and contribute to OpenHarmony talent eco-development.
- **Lako**：brings together a number of schools and companies to form a national community of OpenHarmony (open source gap) intelligent terminals and synagogues.

These models of cooperation not only provide students with opportunities to participate in practical open source projects, but also facilitate the exchange of knowledge and technology between enterprises and higher schools.Through these collaborations, enterprises are better informed about students' abilities and needs, while students at higher education level are given the opportunity to work directly with business specialists, which is valuable in upgrading their technical skills and professional skills.In addition, such cooperation will help to promote the development and diffusion of open source technologies and to contribute more innovative results to open source communities.

### 6.6 Open-source education curriculum is improving <span style="color:red">(未审核)</span>
    
In 2023, efforts in open source education were becoming increasingly visible in Chinese higher education institutions, many of which actively promoted the development of open source education through the introduction of special courses, alliances and cooperation with enterprises.Nearly 100 universities across the country, including the University of Tsinghua, the Beijing University of Aeronautics and Astronautics, Zhejiang University, the Shanghai Transport University and the Ciudad Juárez Pedagogical University, have announced that they will continue their courses on source software over the next three years, including basic courses in open-source specializations, digital public goods and so on, to help students start from scratch and deepen understanding of the open-source knowledge architecture, and to accelerate talent development in key areas of the software.Some specific examples of： are listed below.

- **Beijing University**：
  Working with the Head and GitLink to develop an online practical course on OSS Development Open Source Software Technologies, with sound conclusions and practices and the development of open-source software skills for students.
- **Tsinghua University**：
  Holds an open source operating system training camp in the winter of 2023 to develop the skills of the student operating system through the development of operating system practices in Rust language.
- **Easter Teacher University**：
  - The OSSS101 Open Source Software Knowledge Course was launched with a view to developing open-source awareness and skills among students.
  - The lead was the establishment of the COC Open Source Education Working Group and the creation of an integrated “socio-lessons-certified” open source development system to facilitate the development of open source education.
- **Southern University of Technology**：
  The Association of Open Source Higher Schools was formed at the Congress of the Creative Developers to promote open source ecology and the development of talented students in the Australian Bay region, Cantonese Port of Cantone.
- **Beijing Technical University**：
  In cooperation with the Enlightenment, workshops were held on open-source talent development and cooperation in scientific research, strengthening cooperation in schools and improving the quality of talent development.

The introduction of these activities and courses not only enriches the curriculum system of higher education but also increases the motivation of students to participate in open sources.Through these practices, students can better understand the development process of open source software, acquire relevant skills and participate in open source communities.These initiatives are important for the development of high-quality open-source talent adapted to the development needs of the modern digital economy, as well as for promoting the diffusion and application of open source technology in China.

### 6.7 Open source on campus <span style="color:red">(未审核)</span>
    
In 2023, there was no more visible activity known for open source education than the “open source in schools” carried out by various organizations, including the Open Source Foundation, the Open Source Development Committee, the Open Source Summer and the Red Mountains.

- **Open Atomic Open Source Foundation**
  The Open Atomic Schools Public Interest Project was launched with funding from the Open Atomic Open Source Foundation in partnership with Tencent.Together they explore new paths to the integration of women by establishing open source societies in higher schools, popularizing open source culture, and developing an open source curriculum system.
- **CHC Open Source Development Committee**
  The series of “Open Source Higher Schools” launched by the Open Source Development Committee of the Chinese Academy of Computing has been successfully implemented at Tsinghua, Beijing University, Nord Air North, and Rawal, among others, and has produced a wide range of impact and successful practices.
- **Open Source Summer Organizing Committee**
  In order to provide more students with a better understanding of open source involvement, the open summer's activities have joined many good open source communities to launch the “open summer camp”.The Open Summer School School Series is designed to inject energy and dynamism into the new generation of developers, to increase student knowledge of well-known open source technologies, projects, and communities, both at home and abroad, and to extend open source culture to more institutions.
- **Red Mountain Open Source**
  The Red Mountain Open Source Community has launched the “Red Mountain Open Source Box” campaign to focus high schools and priorities, raising the visibility and visibility of the community and attracting more excellent and innovative resources to participate in the creation of the Open Source project.

Such activities are expected to become one of the mainstream channels of access to open source education for tertiary students in the future.

### 6.8 Open source education policies <span style="color:red">(未审核)</span>

In 2023, despite significant progress in practice in the open-source education sector in China, there were relatively few supportive policies at the policy level.

However, some local governments have begun to focus on and promote the development of open-source education.For example, on 29 December 2022, the Long Way Alliance think tank base proposed “Recommendations for strengthening open source education in Beijing.”The recommendation provides a systematic introduction to the status and bottlenecks of open-source educational talent and proposes that the Beijing municipal government strengthen open-source education and training.As China’s open-source eco-highland, Beijing plays an important role in promoting open-source talent education, which is important for developing software talent to adapt to industry needs, creating open source ecology for sustainable development, upgrading innovation and technology supply capabilities in software science and technology, and leapfrogging to the high end of the innovation chain.

In addition, a joint circular issued by the Ministry of Education and the Ministry of Industry and Informatization in 2020 entitled “Guidance for the Construction of Specified Model Software Colleges (Experimental) has also given a positive impetus to the introduction of open-source education in higher education.The guide focuses on the specializations of software talent development, exploring professional construction patterns and strengthening education on advanced software architecture, engineering and algorithms around the demand for talent in key basic software, large-scale industrial software, industry applications, emerging platform software and embedded software.At the same time, the guide encourage\*\*'s active development of priority open source projects, bringing together good open source\*\* and promoting the software of industrial technology to provide a strong support for industrial innovation.

Although policy messages relating to open sources of education in 2023 were not widely disseminated (possibly in the process of being developed), we have seen the positive impact of existing policy documents on open source education.Looking forward to 2024, the relevant State ministries are expected to introduce more open-source education-related policies to further regulate and promote the practice of open-source education and promote its development in China.

## 7. [Open source ranklists and reports summary](https://hackmd.io/XPCiGt9dRr6K2873L4Pi7Q/) <font color=red>(未审核)
