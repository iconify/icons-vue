<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m07xjf2re"/><path class="y4u-y-e3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-percent-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m07xjf2re {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 22H8a5 5 0 0 1-5-5v-4c0-1.317.335-2.748 1.293-3.707l4-4a5.243 5.243 0 0 1 7.414 0l4 4C20.665 10.252 21 11.683 21 13v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22");
}

.y4u-y-e3d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 7l3 3c.64.64 1 1.72 1 3v4a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4v-4c0-1.28.36-2.36 1-3l4-4a4.243 4.243 0 0 1 6 0zm-2 5l-4 4m0-4h.01M14 16h.01");
}

</style>
