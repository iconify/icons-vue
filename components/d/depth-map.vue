<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1giyo3pl"/><path class="y0gh4eb7e"/><path class="sw4w7sb0q"/><path class="x_if79bzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:depth-map" /></template>
<style>
.b1giyo3pl {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sw4w7sb0q {
  d: path("M8.25 13v-2.75h5.5v5.5H11");
}

.x_if79bzs {
  d: path("M11 10.25V7.5h5.5V13h-2.75");
}

.y0gh4eb7e {
  d: path("M7.25 13h2A1.75 1.75 0 0 1 11 14.75v2a1.75 1.75 0 0 1-1.75 1.75h-2a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 7.25 13");
}

</style>
