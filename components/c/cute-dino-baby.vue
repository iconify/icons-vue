<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="evapiacyp"/><path class="l3r_hhb2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cute-dino-baby" /></template>
<style>
.evapiacyp {
  d: path("M4.5 13L7 15l2.5-2.5L12 15l2.5-2.5L17 15l2.5-2c0 5-3 8.5-7.5 8.5S4.5 18 4.5 13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3r_hhb2m {
  d: path("M8 14V8c0-3.5 2.5-5.5 6-5.5s6 2 6 4.5c0 2-1.5 3-3.5 3h-2v2.5m-2.5-6h.01");
}

</style>
