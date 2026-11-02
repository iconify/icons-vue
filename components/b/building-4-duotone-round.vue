<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s7r_-7b3n"/><path class="rr4fg8bjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-4-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rr4fg8bjn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M5 20V8a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v12m0-11a4 4 0 0 1 4 4v7M9 8h2m-2 4h2");
}

.s7r_-7b3n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 21a1 1 0 0 1-1-1V8a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v12a1 1 0 0 1-1 1ZM9 9h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2m0 4h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2");
}

</style>
