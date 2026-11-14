<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="auhg8vpjy"/><path class="j3dt0vbsf"/><path class="fb5c9juhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-index" /></template>
<style>
.auhg8vpjy {
  d: path("M3 5.25a7 2.75 0 1 0 14 0a7 2.75 0 1 0-14 0Z");
}

.fb5c9juhx {
  d: path("M3 11q0 .068.008.135t.026.135t.042.134t.059.132q.033.067.075.132q.042.066.091.13q.05.065.108.128q.058.064.124.126q.066.063.139.124t.155.12q.081.06.169.118t.184.114q.095.056.198.11q.102.054.211.107q.109.052.224.102q.116.05.237.098q.122.047.249.093q.127.045.26.088t.271.083t.281.078t.29.072t.299.066t.307.061t.314.055t.321.048t.326.043t.331.036t.335.029t.339.023t.341.017t.343.01q.171.003.343.003q1.017 0 1.992-.114m4.273-1.409q.362-.286.549-.597Q17 11.319 17 11m-2.25 4h.01m2.74 0h4m-6.75 3h.01m2.74 0h4m-6.75 3h.01m2.74 0h4");
}

.j3dt0vbsf {
  d: path("M3 5.25V16.5q0 .068.008.135t.026.135t.042.134t.059.132q.033.067.075.132q.042.066.091.13q.05.065.108.128q.058.064.124.126q.066.063.139.124t.155.12t.169.118t.184.114q.095.056.198.11q.102.054.211.107q.109.052.224.102q.116.05.237.098q.122.047.249.093q.127.045.26.088t.271.083t.281.078q.143.037.29.072q.148.034.299.066q.152.032.307.061t.314.055t.321.048q.162.023.326.043t.331.036t.335.029t.339.023t.341.017t.343.01q.171.003.343.003q.989 0 1.94-.108M17 12.163V5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
