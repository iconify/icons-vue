<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tzdfp4-do"/><path class="y6-r88b3l"/><path class="ufzn_r3vk"/><path class="avdamgajo"/><path class="jds7y1b0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:anonymise-duotone-thin" /></template>
<style>
.avdamgajo {
  d: path("M6 21a6 6 0 0 1 12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jds7y1b0v {
  d: path("M7 8a1.5 1.5 0 0 1 1.5 -1.5h7A1.5 1.5 0 0 1 17 8a1.5 1.5 0 0 1 -1.5 1.5h-7A1.5 1.5 0 0 1 7 8");
}

.tzdfp4-do {
  fill: currentColor;
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ufzn_r3vk {
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.y6-r88b3l {
  fill: currentColor;
  d: path("M7 8a1.5 1.5 0 0 1 1.5 -1.5h7A1.5 1.5 0 0 1 17 8a1.5 1.5 0 0 1 -1.5 1.5h-7A1.5 1.5 0 0 1 7 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
