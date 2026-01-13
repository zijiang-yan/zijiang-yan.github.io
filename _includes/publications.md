<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>

<div class="publications">

<!-- <div style="margin: 20px 0px 0px 10px; font-size: 14px;">(* denotes co-first author)</div> -->
<p>* denotes co-first author</p>

<h4 style="margin:0 10px 0;">Preprints</h4>
<ol class="bibliography">
{% for link in site.data.publications.preprints %}
{% include_relative _includes/pub_item.html %}
{% endfor %}
</ol>

<h4 style="margin:0 10px 0;">Journal Papers</h4>
<ol class="bibliography">
{% for link in site.data.publications.journals %}
{% include_relative _includes/pub_item.html %}
{% endfor %}
</ol>

<h4 style="margin:0 10px 0;">Conference Papers</h4>
<ol class="bibliography">
{% for link in site.data.publications.conferences %}
{% include_relative _includes/pub_item.html %}
{% endfor %}
</ol>

</div>
