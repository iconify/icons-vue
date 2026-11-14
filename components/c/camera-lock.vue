<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="npk3-51bl"/><path class="aih25f4na"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-lock" /></template>
<style>
.aih25f4na {
  d: path("M11 12.25h2A1.75 1.75 0 0 1 14.75 14v1A1.75 1.75 0 0 1 13 16.75h-2A1.75 1.75 0 0 1 9.25 15v-1A1.75 1.75 0 0 1 11 12.25m-.5 0V11a1.5 1.5 0 0 1 3 0v1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.npk3-51bl {
  d: path("M3 8.5a2 2 0 0 1 2-2h2.5L9 4h6l1.5 2.5H19a2 2 0 0 1 2 2V18a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>
