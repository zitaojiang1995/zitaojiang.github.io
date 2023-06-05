---
layout: archive
title: "Publications"
permalink: /publications/
years: [2023,2022]
author_profile: true
---
[[Google scholar](https://scholar.google.com/citations?user=U0Jtdr4AAAAJ&hl=en)] | [[Researchgate](https://www.researchgate.net/profile/Zitao_Jiang2)|

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f publication -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Internaltional Proceedings


#### 日本国内会議