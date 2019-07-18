<style>
    .container {
        position: relative;
        width: calc(100vw - 350px);
        height: 50vh;
        padding-bottom: 56.25%;
    }
    .container > iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
</style>

{% include alert.html text="Add your feedback to the PPT specs through GitHub issues (on the left)" %}

<div class="container">
    <iframe
        src='https://view.officeapps.live.com/op/view.aspx?src={{ site.github.repository_url | url_encode }}{{ site.github_raw_root | url_encode }}%2Fassets%2FSSW.PointBank.pptx' 
        frameborder='0'></iframe>
</div>

<p>
    This is a nice view of the <a href="{{ site.github.repository_url }}{{ site.github_source_root | attr_encode }}/assets/SSW.PointBank.pptx">PPTX in GitHub</a>
</p>