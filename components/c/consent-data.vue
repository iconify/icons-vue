<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zbi-0u-js"/><path class="b46s_ne_m"/><path class="ga_0sbckm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consent-data" /></template>
<style>
.b46s_ne_m {
  d: path("M3.5 5.5v12q0 .074.009.147q.009.074.027.147t.045.146t.063.145q.036.073.081.144t.098.142q.053.07.115.14q.062.069.133.137q.07.068.149.135q.079.066.166.131q.086.065.181.128t.197.125q.102.061.212.12t.226.116t.241.112q.124.054.254.106t.266.102q.137.049.279.096t.29.091q.148.043.301.084t.311.079t.321.073q.162.034.328.066q.167.031.337.06t.343.053t.35.046t.355.039t.359.032t.363.026q.182.01.365.018t.367.01q.184.004.368.004q1.124 0 2.199-.132m5.301-6.059V5.5");
}

.ga_0sbckm {
  d: path("M3.5 11.5a7.5 3 0 0 0 15 0M14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zbi-0u-js {
  d: path("M3.5 5.5a7.5 3 0 1 0 15 0a7.5 3 0 1 0-15 0Z");
}

</style>
