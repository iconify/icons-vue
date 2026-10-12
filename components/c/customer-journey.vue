<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="kso3pfbig"/><path class="e73baccim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:customer-journey" /></template>
<style>
.e73baccim {
  d: path("M3.25 21.25h3.5a.5.5 0 0 0 .5-.5C7.25 19.15 6.15 18 5 18s-2.25 1.15-2.25 2.75a.5.5 0 0 0 .5.5m7-2h6a3 3 0 0 0 0-6h-4a3 3 0 0 1 0-6h1.5m3.5 2v-3m0-3.5H21L20 4.5l1 1.75h-3.75Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kso3pfbig {
  cx: 5px;
  cy: 13px;
  r: 2px;
}

</style>
