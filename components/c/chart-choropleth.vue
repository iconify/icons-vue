<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mqge70stp"/><path class="av7wgzbuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-choropleth" /></template>
<style>
.av7wgzbuf {
  fill: currentColor;
  d: path("m2.5 13l6-1v7l-6 2Zm13-8l6-2v8l-6-1Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqge70stp {
  d: path("M3.526 4.658L8.06 3.147a1.5 1.5 0 0 1 .886-.02l6.108 1.746a1.5 1.5 0 0 0 .886-.02l3.586-1.195A1.5 1.5 0 0 1 21.5 5.081v12.838a1.5 1.5 0 0 1-1.026 1.423l-4.534 1.511a1.5 1.5 0 0 1-.886.02l-6.108-1.746a1.5 1.5 0 0 0-.886.02l-3.586 1.195A1.5 1.5 0 0 1 2.5 18.919V6.081a1.5 1.5 0 0 1 1.026-1.423M8.5 3v16m7-14v16m-7-8.5l7-1");
}

</style>
