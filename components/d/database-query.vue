<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wmo9g3s8u"/><path class="a2kr-upic"/><path class="z9qkg3b-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-query" /></template>
<style>
.a2kr-upic {
  d: path("M2.75 5.5v12q0 .068.008.135t.026.135t.042.134t.059.132q.033.067.075.132q.042.066.091.13q.05.065.108.128q.058.064.124.126q.066.063.139.124t.155.12t.169.118t.184.114q.095.056.198.11q.102.054.211.107q.109.052.224.102q.116.05.237.098q.122.047.249.093q.127.045.26.088t.271.083t.281.078q.143.037.29.072q.148.034.299.066q.152.032.307.061t.314.055t.321.048q.162.023.326.043t.331.036t.335.029t.339.023t.341.017t.343.01q.171.003.343.003q.87 0 1.714-.084t1.61-.246m3.676-7.407V5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wmo9g3s8u {
  d: path("M2.75 5.5a7 2.75 0 1 0 14 0a7 2.75 0 1 0-14 0Z");
}

.z9qkg3b-n {
  d: path("M2.75 11.5q0 .068.008.135t.026.135t.042.134t.059.132q.033.067.075.132q.042.066.091.13q.05.065.108.128q.058.064.124.126q.066.063.139.124t.155.12q.081.06.169.118t.184.114t.198.11t.211.107q.109.052.224.102q.116.05.237.098q.122.047.249.093q.127.045.26.088t.271.083t.281.078t.29.072t.299.066t.307.061t.314.055t.321.048t.326.043t.331.036t.335.029t.339.023t.341.017t.343.01q.171.003.343.003q.635 0 1.26-.045t1.219-.133t1.138-.218t1.02-.294m1.696-.888q.329-.275.498-.572t.169-.6m-1.5 6a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

</style>
