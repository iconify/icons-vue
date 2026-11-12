<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e50w2fbus"/><path class="y7ba0nbfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:magnet-duocolor-round" /></template>
<style>
.e50w2fbus {
  stroke-opacity: 0.4;
  d: path("M3 8h5m8 0h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y7ba0nbfs {
  d: path("M3 12V5a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v7a4 4 0 1 0 8 0V5a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v7a9 9 0 0 1-18 0");
}

</style>
