---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Complex Systems and Networks, System Science, IMT Schools for Advanced Studies, Lucca, 2025-2028 (expected)
* M.Eng. in Computer Science and Technology, College of Artificial Intelligence, Southwest University, China, 2022-2025
* B.Eng. in Data Science and Big Data Technology, College of Artificial Intelligence, Southwest University, China, 2019-2023

Work experience
======
  
Skills
======
* Language: Chinese (Native), English (Fluent)
* Programming
  * Commonly Used: Python (NetworkX, numpy, scipy, matplotlib, etc.), MatLab, Mathematica, LateX
  * Studied as Courses: C, C++, Java, R
* Field: Network Science, Game Theory, Mathematical Epidemiology, Stochastic Process

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service
======
* Peer Reviewer for Scientific Reports, Humanities and Social Sciences Communications, Applied Mathematical Modelling, PloS Computational Biology, International Journal of Mathematics for Industry
