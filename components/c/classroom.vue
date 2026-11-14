<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q1to8jb7j"/><path class="dlz1obibu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:classroom" /></template>
<style>
.dlz1obibu {
  d: path("M10.5 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-1.75 5.5c0-2 1.25-2.75 3.25-2.75s3.25.75 3.25 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q1to8jb7j {
  d: path("M5.125 3.5h13.75A2.625 2.625 0 0 1 21.5 6.125v7.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 13.875v-7.75A2.625 2.625 0 0 1 5.125 3.5M7 16.5L5 21m12-4.5l2 4.5");
}

</style>
