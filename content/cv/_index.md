---
title: ""
---

<style>
  /* 覆盖页面容器的限制 */
  .page-body,
  .page-wrapper {
    max-width: none !important;
    padding: 0 !important;
  }
  
  /* CV容器居中 */
  .cv-container {
    width: 100vw;
    height: calc(100vh - 80px);
    position: relative;
    left: 50%;
    right: 50%;
    margin-left: -50vw;
    margin-right: -50vw;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .cv-container iframe {
    width: 90%;
    max-width: 1300px;
    height: 100%;
    border: none;
  }
</style>

<div class="cv-container">
  <iframe 
    src="/CV_202508.pdf" 
    type="application/pdf">
    <p>Your browser does not support PDFs. 
       <a href="/CV_202508.pdf">Download the PDF</a>.</p>
  </iframe>
</div>