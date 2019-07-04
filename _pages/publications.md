---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


**Journal Articles**
<ol>
{% for post in site.journalpublications reversed %}
  {% include archive-single-pubjournal.html %}
{% endfor %}
</ol>


**Conference Papers**
<ol>
{% for post in site.confpublications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}
</ol>
