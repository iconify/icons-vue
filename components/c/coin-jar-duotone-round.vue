<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x5p4owxua"/><path class="h7_x5fbud"/></g>`;
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

.x5p4owxua {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m7 2a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M17 12v1.586l.707.707C18.665 15.252 19 16.683 19 18v1a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-1c0-1.317.335-2.748 1.293-3.707L7 13.586V12a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1");
}

</style>
