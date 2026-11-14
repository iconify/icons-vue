<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zmsqe4bvr"/><path class="t38734bbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:health-network" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t38734bbh {
  d: path("M3 17.5a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m-1 4a2.5 2.5 0 0 1 5 0m3.5-4a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m-1 4a2.5 2.5 0 0 1 5 0m3.5-4a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m-1 4a2.5 2.5 0 0 1 5 0");
}

.zmsqe4bvr {
  d: path("M10.5 2.5h3v2h2v3h-2v2h-3v-2h-2v-3h2Zm1.5 7V16m-7.5 0v-3h15v3");
}

</style>
