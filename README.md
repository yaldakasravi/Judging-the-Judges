# Perception of AI vs Human Ethical Reasoning

This project investigates how people perceive and respond to ethical reasoning provided by Large Language Models (LLMs), like ChatGPT, compared to responses from other humans. It explores whether attributing a moral argument to an AI system impacts a participant’s trust, openness to revise opinions, or defensiveness—especially in ethically sensitive contexts.

## 🔍 Abstract

Large language models are increasingly used in domains requiring complex ethical reasoning—autonomous vehicles, healthcare, and workplace decisions. This study evaluates participants’ perceptions of LLM-generated versus human-generated responses across four ethically sensitive themes:
- Autonomous vehicle dilemmas
- Medical resource allocation
- Variants of the trolley problem
- Workplace conflicts

Using a mixed-methods and between-subjects experimental design, we analyzed how participants revise their beliefs when presented with an opposing viewpoint that was either human- or LLM-attributed. Our results show:
- Higher trust and willingness to revise opinions when responses are perceived as human-generated.
- Greater skepticism and defensiveness toward AI-generated reasoning.
- Distinct perceptions of trustworthiness, relatability, and moral credibility based on the source.

These findings have implications for the ethical deployment of LLMs and the design of AI systems that interact with human users in morally charged decision-making contexts.


## 📊 Methods

- **Study Design**: Between-subjects survey with N = [insert number] participants, randomized to read either human- or LLM-attributed ethical arguments.
- **Data Collection**: Likert-scale trust & attitude questions + open-ended justifications.
- **Quantitative Analysis**: T-tests, chi-square tests, regression (see R Notebook).
- **Qualitative Analysis**: Thematic coding of open responses using [insert method/tool].

## 📈 Key Findings

- Participants revise their moral stance more when they think a human disagrees with them.
- LLM-attributed responses were often dismissed as less authentic or less morally grounded.
- Even when identical, responses perceived as coming from LLMs were rated lower in credibility.

## 📦 Dependencies

Install these R packages before running the notebook:

```r
install.packages(c("tidyverse", "ggplot2", "dplyr", "ggpubr", "readr"))

git clone https://github.com/yaldakasravi/ai-vs-human-ethics.git


