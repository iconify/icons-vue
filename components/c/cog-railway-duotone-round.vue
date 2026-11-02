<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u91s7e-0x"/><path class="en_nr7bjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cog-railway-duotone-round" /></template>
<style>
.en_nr7bjl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 19V9a2 2 0 0 1 2-2h3V6a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v7zm0-7h5V9h7m-7-2v2M4 20l16-8M6 19l1 2m3-4l1 2m3-4l1 2m3-4l1 2");
}

.ft5dv1b6b {
  fill: none;
}

.u91s7e-0x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 9a3 3 0 0 1 3-3h2a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v7a1 1 0 0 1-.553.894l-12 6A1 1 0 0 1 5 19Z");
}

</style>
