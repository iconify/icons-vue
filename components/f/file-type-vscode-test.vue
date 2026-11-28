<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bfjbytbni"/><path class="k69tw7bib"/><path class="etis1zded"/><path class="it24_abss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vscode-test" /></template>
<style>
.bfjbytbni {
  fill: var(--svg-color--0065a9, #0065a9);
  d: path("m28.253 4.815l-5.43-2.614a1.64 1.64 0 0 0-1.874.318L3.173 18.726a1.1 1.1 0 0 0-.076 1.551q.035.038.073.073l1.451 1.318a1.1 1.1 0 0 0 1.402.062L27.435 5.493a1.09 1.09 0 0 1 1.75.869v-.063a1.65 1.65 0 0 0-.932-1.484");
}

.etis1zded {
  fill: var(--svg-color--1f9cf0, #1f9cf0);
  d: path("M22.822 28.094a1.64 1.64 0 0 1-1.873-.318a.965.965 0 0 0 1.644-.683V3.2a.964.964 0 0 0-1.648-.682a1.64 1.64 0 0 1 1.874-.32l5.43 2.612a1.65 1.65 0 0 1 .936 1.483V24a1.65 1.65 0 0 1-.933 1.484Z");
}

.it24_abss {
  fill: var(--svg-color--275fb0, #275fb0);
  d: path("M12.337 29.909a3.626 3.626 0 0 1-2.854-4.298c.239-1.007.188-.949 5.392-6.392l4.898-5.125l1.39 1.319l-5.65 5.899l4.723-.102l3.34-3.484l1.384 1.331l-4.91 5.114c-4.504 4.692-4.95 5.135-5.408 5.361a3.67 3.67 0 0 1-2.31.37zm13.81-11.758c-.13-.077-1.457-1.318-2.948-2.75l-2.711-2.611l-.009-.397a.8.8 0 0 1 .183-.634a.93.93 0 0 1 .977-.352a65 65 0 0 1 5.911 5.673a.942.942 0 0 1-1.405 1.067z");
}

.k69tw7bib {
  fill: var(--svg-color--007acc, #007acc);
  d: path("m28.253 25.479l-5.43 2.615a1.64 1.64 0 0 1-1.874-.318L3.173 11.568a1.1 1.1 0 0 1-.076-1.551q.035-.038.073-.073l1.45-1.318a1.1 1.1 0 0 1 1.405-.062L27.436 24.8a1.09 1.09 0 0 0 1.75-.869V24a1.65 1.65 0 0 1-.933 1.479");
}

</style>
