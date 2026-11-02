<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pp7dwpnny"/><path class="i7azk4brk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:linux-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i7azk4brk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 9h.01M14 9h.01M10 12h4l-2 2Zm-2 9c0-2 2-4 4-4s4 2 4 4M3 21c1-2 3-5 3-9V9a6 6 0 1 1 12 0v3c0 4 2 7 3 9");
}

.pp7dwpnny {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 12V9a7 7 0 1 1 14 0v3c0 1.432.293 2.85.784 4.192q.336.906.762 1.772c.257.528.533 1.046.811 1.564c.182.34.365.68.537 1.025a.997.997 0 0 1-.447 1.341A1 1 0 0 1 21 22H3a1 1 0 0 1-.894-1.447c.172-.345.355-.685.537-1.025c.278-.518.554-1.036.811-1.564q.426-.867.762-1.772C4.707 14.85 5 13.432 5 12");
}

</style>
