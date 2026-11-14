<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y4rq56bwb"/><path class="yq_n3tbgc"/><path class="yv3gu2bmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hidden-disability" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4rq56bwb {
  d: path("m6.5 2.5l5.5 8l5.5-8");
}

.yq_n3tbgc {
  d: path("M16 16a2 2 0 0 1-2 3.5a2 2 0 0 1-4 0A2 2 0 0 1 8 16a2 2 0 0 1 2-3.5a2 2 0 0 1 4 0a2 2 0 0 1 2 3.5");
}

.yv3gu2bmi {
  d: path("M10.5 16a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
