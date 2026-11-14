<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y7g-1v32z"/><path class="tr3gnsblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ancestral-tablet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tr3gnsblk {
  d: path("M11 6.75h2a1.75 1.75 0 0 1 1.75 1.75V14A1.75 1.75 0 0 1 13 15.75h-2A1.75 1.75 0 0 1 9.25 14V8.5A1.75 1.75 0 0 1 11 6.75m1 2.75V13");
}

.y7g-1v32z {
  d: path("M6.5 18.5v-13q5.5-3.5 11 0v13M5.5 20l.555-.832a1.5 1.5 0 0 1 1.248-.668h9.394a1.5 1.5 0 0 1 1.248.668L18.5 20a.965.965 0 0 1-.803 1.5H6.303A.965.965 0 0 1 5.5 20");
}

</style>
