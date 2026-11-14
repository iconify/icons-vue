<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="knbwpobbk"/><path class="l5h09tb0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:driving-cab" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knbwpobbk {
  d: path("M9.25 2.5h5.5A5.25 5.25 0 0 1 20 7.75v6.5a5.25 5.25 0 0 1-5.25 5.25h-5.5A5.25 5.25 0 0 1 4 14.25v-6.5A5.25 5.25 0 0 1 9.25 2.5");
}

.l5h09tb0h {
  d: path("M8.75 5.5h6.5A1.75 1.75 0 0 1 17 7.25v1.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 8.75v-1.5A1.75 1.75 0 0 1 8.75 5.5M7.5 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M8 19.5l-1.5 2m9.5-2l1.5 2");
}

</style>
