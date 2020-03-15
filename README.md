# Identification of social relation within pedestrian dyads
Source code used for deriving the results reported in our PLoS One (2019) and PED-2018 articles

This repository contains the source code relating the results reported in our PLoS One (2019) and PED-2018 articles [1,2]. 

Our study focuses on social pedestrian groups in public spaces and makes an effort to identify the type of social relation between the group members. As a first step for this identification problem, we focus on dyads (i.e. 2 people groups). Moreover, as a mutually exclusive categorization of social relations, we consider the domain-based approach of Bugental [3], which precisely corresponds to social relations of colleagues, couples, friends and families, and identify each dyad with one of those relations. For this purpose, we use anonymized trajectory data (freey available at [4]) and derive a set of observables thereof, namely, inter-personal distance, group velocity, velocity difference and height difference. Subsequently, we use the probability density functions (pdf) of these observables as a tool to understand the nature of the relation between pedestrians. To that end, we propose different ways of using the pdfs. Namely, we introduce a probabilistic Bayesian approach and contrast it to a functional metric one and evaluate the performance of both methods with appropriate assessment measures. 

Our study stands out as the first attempt to automatically recognize social relation between pedestrian groups. Additionally, in doing that it uses completely anonymous data and proves that social relation is still possible to recognize with a good accuracy without invading privacy. In particular, our findings indicate that significant recognition rates can be attained for certain categories and with certain methods. Specifically, we show that a very good recognition rate is achieved in distinguishing colleagues from leisure-oriented dyads (families, couples and friends), whereas the distinction between the leisure-oriented dyads results to be inherently harder, but still possible at reasonable rates, in particular if families are restricted to parent-child groups. In general, we establish that the Bayesian method outperforms the functional metric one due, probably, to the difficulty of the latter to learn observable pdfs from individual trajectories.

**References**

[1] Zeynep Yücel, Francesco Zanlungo, Claudio Feliciani, Adrien Gregorj, Takayuki Kanda;
Identification of social relation within pedestrian dyads;
PloS One, doi: 10.1371/journal.pone.0223656, Oct. 2019.
https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0223656

[2] Zeynep Yücel, Francesco Zanlungo, Claudio Feliciani, Adrien Gregorj, Takayuki Kanda;
Estimating social relation from trajectories;
Pedestrian and Evacuation Dynamics, PED 2018.

[3] DB Bugental DB; Acquisition of the algorithms of social life: A domain-based approach; Psychological Bulletin. 2000; 126(2):187. pmid:10748640 

[4] ATR-IRC. Dataset: Pedestrian tracking with group annotations; http://www.irc.atr.jp/sets/groups/. 
