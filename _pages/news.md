---
layout: archive
permalink: /news/
title: "News"
author_profile: true
redirect_from:
  - /year-archive/
---

<div style="line-height: 1.8;">
{% for item in site.data.news %}
  {% include news-badge.html item=item %}
{% endfor %}
</div>