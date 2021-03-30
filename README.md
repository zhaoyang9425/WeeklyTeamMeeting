## WeeklyTeamMeeting
paper sharing

### Voice Conversion
Cotatron: Transcription-Guided Speech Encoder for Any-to-Many Voice Conversion without Parallel Data

[paper](./paper/Cotatron-%20Transcription-Guided%20Speech%20Encoder%20for%20Any-to-Many%20Voice%20Conversion%20without%20Parallel%20Data.pdf)
[slides](./slides/wr_Pre0311.pptx)
<details>
<summary>概述</summary>
大家好，这是我下周分享的文章。
文章提出了Cotatron模型，基于预训练的多说话人TTS架构的语音转换系统，作者构建的Cotatron特征将转录信息和给定语音进行对齐，
该方法在自然度和说话人相似性方面都优于先前的方法，同时还可以进行任意对多的转换任务，并利用自动语音识别来自动转录。
</details>

A Batch Normalized Inference Network Keeps the KL Vanishing Away

[paper](./paper/A%20Batch%20Normalized%20Inference%20Network%20Keeps%20the%20KL%20Vanishing%20Away.pdf)
<details>
<summary>概述</summary>
这是我下周分享的是发表在ACL 2020的一篇文章，作者来自佛罗里达大学与腾讯AL Lab。
文章主要说的是VAE将变分推理和深度神经网络相结合来逼近潜在变量的后验分布。当与强自回归解码器配对时，VAE往往收敛于退化的局部最优解，称为“posterior collapse”。文章提出了一种简单的使用批量归一化的方法，通过正则化近似后验参数的分布来设置期望的下界有效防止后验崩溃。
文章方法在语言建模、文本分类和对话生成方面超越了强自回归基线，在保持与VAE几乎相同的训练时间的同时，可以与更复杂方法的效果相抗衡。
</details>

Exploring Phoneme-Level Speech Representations for End-to-End Speech Translation

[paper](./paper/Exploring%20Phoneme-Level%20Speech%20Representations%20for%20End-to-End%20Speech%20Translation.pdf)
<details>
<summary>概述</summary>
大家好，这是我下周一分享的文章，发表在ACL 2019。先前的端到端的翻译任务主要使用帧级特征表示语音，产生的序列存在不足。
本文提出了新的更有效的方法，即创建与音素相似的语音表示形式。
</details>

Towards Practical Lipreading with Distilled and Efficient Models

[paper](./paper/TOWARDS%20PRACTICAL%20LIPREADING%20WITH%20DISTILLED%20AND%20EFFICIENT%20MODELS.pdf)
[slides](./slides/Toward_pratical_lipreading_with_distilled_and_efficient_models.pptx)
<details>
<summary>概述</summary>
大家好，这是我下周四分享的icassp2021上的文章。
文章是唇语识别实际部署方面的研究，通过知识蒸馏和深度可分离的卷积，在减少参数量的基础上得到效果与sota相近的模型
</details>

Google’s Multilingual Neural Machine Translation System: Enabling Zero-Shot Translation

[paper](./paper/Google’s%20Multilingual%20Neural%20Machine%20Translation%20System-Enabling%20Zero-Shot%20Translation.pdf)
<details>
<summary>概述</summary>
大家好，这是我下周四要分享的文章，由Google发表，提出了一种简洁却行之有效的方法，
通过对输入数据进行处理在不改变通用NMT架构的前提下实现了对多语言翻译模型的构建与训练，不仅在一对多/多对一/多对多场景下取得了不错的效果，
同时还实现了两种语言间的零数据翻译。
</details>

Multilingual Speech Recognition with Corpus Relatedness Sampling

[paper](./paper/Multilingual%20Speech%20Recognition%20with%20Corpus%20Relatedness%20Sampling.pdf)
<details>
<summary>概述</summary>
大家好，这是我下周要分享的文章，本文主要用于低资源语音识别，
已有的研究方法多为先在一些语料上面进行预训练，然后再针对目标语言精调。
论文中所提出的方法利用语料相关性的采样策略。将输入的语音特征和语料 embedding 联合起来作为整个模型的输入。
实验结果证明，这种采样策略训练得到的声学模型，在音素错误率（PER）上与其他的对比实验相比，有明显的性能提升。
</details>

FastBERT: a Self-distilling BERT with Adaptive Inference Time

[paper](./paper/FastBERT%20a%20Self-distilling%20BERT%20with%20Adaptive%20Inference%20Time.pdf)
<details>
<summary>概述</summary>
大家好，这是我下周一分享的文章，文章是自监督模型轻量化方面的研究，
文中设计了一种自蒸馏的BERT，该模型能够适应性的调整推理时间。实验结果表明该模型能够在保证一定性能的情况下将推理速度提升1-12倍。
</details>

Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting

[paper](./paper/Informer-%20Beyond%20Efficient%20Transformer%20for%20Long%20Sequence%20Time-Series%20Forecasting.pdf)
<details>
<summary>概述</summary>
大家好，这是我下周将要分享的一篇AAAI2021的best paper，作者是北航的博士生。 
这篇文章针对Transformer存在的一系列问题，如二次时间复杂度、高内存使用率以及Encoder-Decoder的结构限制，提出了一种Informer模型来用于提高长序列的预测问题。
</details>

Character-Level Translation with Self-attention

[paper](./paper/Character-Level%20Translation%20with%20Self-attention.pdf)
[slides](./slides/Character-Level%20Translation%20with%20Self-attention.pptx)
<details>
<summary>概述</summary>
大家好，这是我下周分享的文章，发表在ACL2020。
文章探讨了self-attention在字符级神经机器翻译中的适应性，提出了一种transformer的变体，
这种变体在单语言翻译和多语言翻译中均取得优于标准transformer的效果。
</details>
