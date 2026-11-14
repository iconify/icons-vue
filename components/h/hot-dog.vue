<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jxz2abb0r"/><path class="fs4-8kd3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-dog" /></template>
<style>
.fs4-8kd3k {
  d: path("M3.644 16.63L19.208 5.732l1.434 2.048L5.078 18.678Z");
}

.jxz2abb0r {
  d: path("m3.378 14.07l13.516-9.464a1.25 1.25 0 0 1 1.741.307l2.294 3.276a1.25 1.25 0 0 1-.307 1.741L7.106 19.394a1.25 1.25 0 0 1-1.741-.307l-2.294-3.276a1.25 1.25 0 0 1 .307-1.741Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
