<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="woigj_buw"/><path class="vfoa9ubnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-express" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfoa9ubnw {
  d: path("M8.75 8.25L15 12l6.25-3.75M15 12v7.25M3.5 8.5H6M2.5 12H6m-2.5 3.5H6");
}

.woigj_buw {
  d: path("m15.855 5.229l4.5 2.52a1.75 1.75 0 0 1 .895 1.527v5.448a1.75 1.75 0 0 1-.895 1.527l-4.5 2.52a1.75 1.75 0 0 1-1.71 0l-4.5-2.52a1.75 1.75 0 0 1-.895-1.527V9.276a1.75 1.75 0 0 1 .895-1.527l4.5-2.52a1.75 1.75 0 0 1 1.71 0");
}

</style>
