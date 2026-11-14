<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mrtlb5e1m"/><path class="q03s1s14v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-answer" /></template>
<style>
.mrtlb5e1m {
  d: path("M15.4 20H3V4h18v11.4M6.5 8.5h7m-7 4h11m-11 4h5");
}

.q03s1s14v {
  d: path("M18.5 15.5q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
