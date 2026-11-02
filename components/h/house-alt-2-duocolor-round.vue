<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ra34vcrze"/><path class="gj6r29cyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-duocolor-round" /></template>
<style>
.gj6r29cyu {
  d: path("M3 20h18M5 20v-7c0-1.28.36-2.36 1-3l3-3a4.243 4.243 0 0 1 6 0l3 3c.64.64 1 1.72 1 3v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ra34vcrze {
  stroke-opacity: 0.4;
  d: path("M10 20v-4a2 2 0 1 1 4 0v4");
}

</style>
