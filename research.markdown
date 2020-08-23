---
layout: research
title: Research
permalink: /research/
subtitile: Research Highlights
---


### ACAT (Aggregated Cauchy Association Test)


ACAT [[R package](https://github.com/yaowuliu/ACAT)] is a generic method that utilizes the Cauchy distribution to effectively combine correlated p-values. It first transforms the individual p-values to Cauchy variables, then takes the (weighted) summation of them as the test statistic. 

<p align="center">
<img src="https://raw.githubusercontent.com/yaowuliu/yaowuliu.github.io/master/assets/ACAT.png" width="500"/>
</p>


#### Key features

* The overall p-value of ACAT can be accurately approximated by a Cauchy distribution **without** the need to account for the correlations among individual p-values.

* Super fast computation

* Powerful when signals are sparse

#### Reference

**Liu, Y.** and Xie, J.(2020). Cauchy combination test: a powerful test with analytic p-value calculation under arbitrary dependency structures. *Journal of the American Statistical Association.* 115(529), 393-402.

**Liu, Y.**, Chen, S., Li, Z., Morrison, A.C., Boerwinkle, E., and Lin, X. (2019). ACAT: a fast and powerful p-value combination method for rare-variant analysis in sequencing studies. *The American Journal of Human Genetics.* 104(3), 410-421.
