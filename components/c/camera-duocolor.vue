<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4rnrvbzy"/><path class="holxvob5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-duocolor" /></template>
<style>
.holxvob5s {
  d: path("m7 7l2-2c.64-.64 1.36-1 2-1h2c.64 0 1.36.36 2 1l2 2h2a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y4rnrvbzy {
  stroke-opacity: 0.4;
  d: path("M9 13a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
