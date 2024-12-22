---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Resume/CV Download](/files/resume.pdf)

Education
======
* Ph.D in Artificial Intelligence, Oregon State University, 2028 (expected)
* M.S. in Artificial Intelligence, Oregon State University, 2025 (expected)
* B.A. in Mathematics, Colby College, 2022
* B.A. in Computer Science, Colby College, 2022

Work experience
======
* Summer 2021: NSF REU Undergraduate Researcher
  * Montana State University
  * Worked on the Circular Pattern Matching problem with applications to malware detection and DNA analysis.
  * Supervisor: Dr. Brendan Mumey, Dr. Clemente Izurieta

* Fall 2020 - Spring 2022: Undergraduate Research Assistant
  * Colby College
  * Worked with an interdisciplinary team to analyze the structure of water molecules using evolutionary algorithms.
  * Supervisor: Dr. Eric Aaron, Dr. Lindsey Madison
  
Skills
======
* Programming
  * Python/Numpy/Pytorch
  * MATLAB

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
  
Service and leadership
======
* Secretary of Finance, Aritificial Intelligence Graduate Student Association, Oregon State University
* Volunteer Reviewer, AI Admitted Students Program, Oregon State University
