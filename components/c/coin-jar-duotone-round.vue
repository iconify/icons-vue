<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rammd-b9p"/><path class="h7_x5fbud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coin-jar-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h7_x5fbud {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12v2l-1 1c-.64.64-1 1.72-1 3v1a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-1c0-1.28-.36-2.36-1-3l-1-1v-2m-9 0h10M6 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m7 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.rammd-b9p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 5a2 2 0 1 1 3.999-.001A2 2 0 0 1 6 5m7 2a2 2 0 1 1 3.999-.001A2 2 0 0 1 13 7m-5 5h8v2l1 1c.763.764 1 1.959 1 3v1a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-1c0-1.041.237-2.236 1-3l1-1Z");
}

</style>
