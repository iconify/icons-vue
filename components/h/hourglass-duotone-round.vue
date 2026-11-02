<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iqrud2b7g"/><path class="mqzyzub0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iqrud2b7g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 2a1 1 0 0 1 1 1v2c0 1.317-.335 2.748-1.293 3.707L13.414 12l3.293 3.293C17.665 16.252 18 17.683 18 19v2a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-2c0-1.317.335-2.748 1.293-3.707L10.586 12L7.293 8.707C6.335 7.748 6 6.317 6 5V3a1 1 0 0 1 1-1Z");
}

.mqzyzub0t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3v2c0 1.28.36 2.36 1 3l4 4l-4 4c-.64.64-1 1.72-1 3v2M17 3v2c0 1.28-.36 2.36-1 3l-4 4l4 4c.64.64 1 1.72 1 3v2M5 3h14M5 21h14");
}

</style>
