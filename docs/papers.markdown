---
layout: "home"
title: "Papers"
---

# Drafts and Pre-Prints

1. Zachary Grannan and Alexander J. Summers. *Resource Specifications for
   Resource-Manipulating Programs*. 2024. <a
   href="https://arxiv.org/abs/2304.12530" target="_blank" rel="noopener
   noreferrer">[arXiv link]</a>

# Conference Papers

<ol>
{% for paper in site.data.papers %}
    <li style="margin-bottom: 10px;">
    {{ paper.authors }}. "{{ paper.title }}." <i>{{ paper.venue }}</i>, {{ paper.year }}.
    </li>
{% endfor %}
</ol>
