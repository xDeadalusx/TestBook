---
redirect_from:
  - "/01/introductionmotivation"
interact_link: content/E:\Git\DataDrivenMethods\TestBook\content\01/IntroductionMotivation.ipynb
kernel_name: python3
has_widgets: false
title: 'IntroMot'
prev_page:
  url: /01/Intro.html
  title: 'Intro'
next_page:
  url: /01/InstallingJupyter.html
  title: 'Install'
comment: "***PROGRAMMATICALLY GENERATED, DO NOT EDIT. SEE ORIGINAL FILES IN /content***"
---


# Introduction and Motivation

The field of data science has seen an incredible growth in the recent decades and methods that were once only used by IT experts made their way to other fields of science, such as chemical engineering. A famous headline from *The Economist* from 2017 read:

**The world's most valuable resource is no longer oil, but data** <sup>[1]</sup>

All big chemical companies already know that they will only be competitive in the long run if they are able to extract the most out of the massive amounts of data that they assemble every day. They actively search for chemical engineers with specialization in data driven analysis methods to help them optimize their processes with the power of data. Hence, engineers with knowledge about data driven methods will have a distinct advantage over their peers in the coming years.

## Application areas of data driven methods:

While there are already interesting applications in chemical engineering, it is clear that this research field is still in a very early stage and we will most probably see much more applications in the coming years and decades. At the time of writing, there are three broad fields in chemical engineering where data driven methods have been used successfully

**Fault detection and diagnosis:**

A *fault* in a chemical plant is defined as an unpermitted deviation of at least one characteristic property or variable of the system. The types of faults occurring in industrial systems include process parameter changes, disturbance parameter changes, actuator problems, and sensor problems. Catalyst poisoning and heat exchanger fouling are examples of process parameter changes. A disturbance parameter change can be an extreme change in the concentration of a process feed stream or in the ambient temperature. An example of an actuator problem is a sticking valve, and a sensor producing biased measurements is an example of a sensor problem <sup>[2]</sup>. 
    
**Materials design:**

Materials design offers another opportunity, where we have the important and challenging problem of discovering and designing new materials and formulations with desired properties. This encompasses a wide variety of products such as catalysts, nano-structures, pharmaceuticals, additives, polymeric composites, rubber compounds, and alloys. The Holy Grail is to be able to design or discover materials with desired macroscopic properties rationally, systematically, and quickly, rather than by the slow and expensive trial-and-error Edisonian approach that has predominated for decades <sup>[3]</sup>.

**Process modeling and optimization:**

While many processes can be (at least partially) described/modeled by knowledge about the underlying physical phenomena (so called mechanistic or phenomenological models), there are examples where we lack this understanding, examples include...

To still be able to simulate and optimize these systems, we can make use of data that has been collected for these processes. If we do not have any knowledge about the system, we may fit an adequate model (e.g. an artificial neural network, support vector machine, etc.) to the available data. If, on the other hand, we have at least some mechanistic understanding of the system (e.g. basic mass balances), we may use this knowledge and use machine learning techniques only for the part that we do not have information about (e.g. detailed kinetic expressions). The combination of mechanistic and data driven models is referred to as hybrid modeling. We can use these models to gain a deeper understanding of the system and to optimize it.


# References

[1] https://www.economist.com/leaders/2017/05/06/the-worlds-most-valuable-resource-is-no-longer-oil-but-data

[2] Russell, E. L., Chiang, L. H., Braatz, R. D., *[Data-driven Methods for Fault Detection and Diagnosis in Chemical Processes](https://www.springer.com/de/book/9781447111337)*, Springer 2000

[3] Venkatasubramanian, V., *[The promise of artificial intelligence in chemical engineering: Is it here, finally?](dx.doi.org/10.1002/aic.16489)*, AIChE Journal, 65(2), 2019, 466--478

