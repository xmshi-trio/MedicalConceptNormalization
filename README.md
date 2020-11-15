# Medical Concept Normalization

![](https://img.shields.io/badge/Status-building-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red)

> Contributed by Xiaoming Shi. This repo contains a list of summarization papers including various topics. If any error, please open an issue, and I am pleased to hear from you.

## Content
* [Task Overview](#Task Overview)
* [Dataset](#Dataset)
* [Paper list](#Paper list)

## Task Overview
**Task Definition** Concept normalization is a task that maps concept mentions, the in-text natural-language mentions of ontological concepts, to concept entries in a standardized ontology or knowledge base. (Word sense disambiguation)

<!--
2. **Task Category**
   2.1 clinical disorder normalization in 2013 ShARe/CLEF [[pdf]](https://link.springer.com/chapter/10.1007%2F978-3-642-40802-1_24)
   - Three subtasks:
   1) Identification and normalisation of disorders and normalisation of abbreviations and acronyms
   2) Clinical reports terminology standards as well as information retrieval
   3) Address questions patients may have when reading clinical reports
   - Data Source: De-identified clinical reports from US intensive care and originated from the MIMIC II database

   2.2 2014 SemEval Task 7 Analysis of Clinical Text [[pdf]](https://www.aclweb.org/anthology/S14-2007.pdf)
    - Two subtasks: 
   1) Identification 
   2) Normalization (Task B) of diseases and disorders in clinical reports
    - Data source: discharge summaries, electrocardiogram, echocardiogram, and radiology reports from a US intensive care department

   2.3 Adverse Drug Event Normalization in Social Media Mining for Health (SMM4H) [[pdf]](https://pubmed.ncbi.nlm.nih.gov/30272184/)
   - Three subtasks: 
   1) adverse drug reactions (ADRs) 
   2) medication consumption, from medication-mentioning tweets 
   3) normalization of ADR expressions
   - Data source: Twitter
-->

## Dataset

|ID|Name|Description|Paper|Conference|# of Samples|# of Concepts|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | TwADR-S | [Twitter](https://twitter.com/home) | **Adapting phrase-based machine translation to normalise medical terms in social media messages** [[pdf]](https://www.aclweb.org/anthology/P16-1096.pdf) | EMNLP 2015 |201|58|
| 2 | TwADR-L | [Twitter](https://twitter.com/home) | **Normalising Medical Concepts in Social Media Texts by Learning Semantic Representation** [[pdf]](https://www.aclweb.org/anthology/P16-1096.pdf) | ACL 2016 |5,074|2,220|
| 3 | AskAPatient | [AskAPatient](https://www.askapatient.com/) | **Normalising Medical Concepts in Social Media Texts by Learning Semantic Representation** [[pdf]](https://www.aclweb.org/anthology/P16-1096.pdf) | ACL 2016 |17,324|1,036|
| 4 | SMM4H-17 | [Twitter](https://twitter.com/home) | **Data and systems for medication-related text classification and concept normalization from Twitter: insights from the Social Media Mining for Health (SMM4H)-2017 shared task** [[pdf]](https://pubmed.ncbi.nlm.nih.gov/30272184/) | JAMIA 2018 |9,149|22,500|
| 5 | MCN | [Twitter](https://twitter.com/home) | **Data and systems for medication-related text classification and concept normalization from Twitter: insights from the Social Media Mining for Health (SMM4H)-2017 shared task** [[pdf]](https://pubmed.ncbi.nlm.nih.gov/30272184/)| JAMIA 2018 |9,149|22,500|
| 6 | CHIP 2019 | clinical procedures extracted from Chinese electronic medical records | **A Knowledge-driven Generative Model for Multi-implication Chinese Medical Procedure Entity Normalization** [[pdf]](https://www.aclweb.org/anthology/2020.emnlp-main.116.pdf) | EMNLP 2020|4,000|9,867|

## Paper list
### Overview Paper
1. **Overview of the ShARe/CLEF eHealth Evaluation Lab 2013** [[pdf]](https://link.springer.com/chapter/10.1007%2F978-3-642-40802-1_24). In Proc. of Information Access Evaluation.
2. **SemEval-2014 Task 7: Analysis of Clinical Text** [[pdf]](https://www.aclweb.org/anthology/S14-2007.pdf). In Proc. of SemEval 2014.
3. **Data and systems for medication-related text classification and concept normalization from Twitter: insights from the Social Media Mining for Health (SMM4H)-2017 shared task** [[pdf]](https://pubmed.ncbi.nlm.nih.gov/30272184/). In Proc. of JAMIA 2018.
4. **Overview of the Fourth Social Media Mining for Health (#SMM4H) Shared Task at ACL 2019** [[pdf]](https://www.aclweb.org/anthology/W19-3203.pdf). In Proc. of ACL 2019 Workshop.

### Paper for String-Matching or Dictionary Look-up Approach
1. **ULisboa: Recognition and Normalization of Medical Concepts** [[pdf]](https://www.aclweb.org/anthology/S15-2070.pdf). In Proc. of SemEval 2015.
2. **Sieve-Based Entity Linking for the Biomedical Domain** [[pdf]](https://www.aclweb.org/anthology/P15-2049.pdf). In Proc. of ACL/IJCNLP 2015.
3. **AuDis: an automatic CRF-enhanced disease normalization in biomedical text** [[pdf]](https://academic.oup.com/database/article/doi/10.1093/database/baw091/2630473). In Proc. of Database 2016.

### Paper for Supervised Multi-Class Classifiers
1. **Adapting phrase-based machine translation to normalise medical terms in social media messages** [[pdf]](https://www.aclweb.org/anthology/P16-1096.pdf). In Proc. of EMNLP 2015.
2. **Normalising Medical Concepts in Social Media Texts by Learning Semantic Representation** [[pdf]](https://www.aclweb.org/anthology/P16-1096.pdf). In Proc. of ACL 2016.
2. **Using an Ensemble of Generalised Linear and Deep Learning Models in the SMM4H 2017 Medical Concept Normalisation Task** [[pdf]](http://ceur-ws.org/Vol-1996/paper10.pdf). In Proc. of CEUR Workshop 2017.
3. **Medical concept normalization in social media posts with recurrent neural networks** [[pdf]](https://doi.org/10.1016/j.jbi.2018.06.006). In Proc. Journal of Biomedical Informatics 2018.
4. **Multi-task CharacterLevel Attentional Networks for Medical Concept Normalization** [[pdf]](https://doi.org/10.1007/s11063-018-9873-x). In Proc. of Neural Process Lett 2019.
5. **A Hybrid Normalization Method for Medical Concepts in Clinical Narrative using Semantic Matching** [[pdf]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6568138/). In Proc. of AMIA 2019.

### Paper for Generator and Ranker
1. **A Generate-and-Rank Framework with Semantic Type Regularization for Biomedical Concept Normalization** [[pdf]](https://www.aclweb.org/anthology/2020.acl-main.748.pdf). In Proc. of ACL 2020.
2. **A Knowledge-driven Generative Model for Multi-implication Chinese Medical Procedure Entity Normalization** [[pdf]](https://www.aclweb.org/anthology/2020.emnlp-main.116.pdf). In Proc. of EMNLP 2020.