<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xukwp3b5k"/><path class="afmmmhbmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-square-duotone-round" /></template>
<style>
.afmmmhbmu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5a2 2 0 1 1 4 0a2 2 0 0 1-4 0m7 5l11 4l-5 2l-2 5z");
}

.ft5dv1b6b {
  fill: none;
}

.xukwp3b5k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 5a2 2 0 1 1 3.999-.001A2 2 0 0 1 3 5m7 5l11 4l-5 2l-2 5Z");
}

</style>
