<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lz692cbkn"/><path class="hf9kdwbci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-duocolor" /></template>
<style>
.hf9kdwbci {
  d: path("M5 6a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Zm10 0a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1ZM5 8H4a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h1m14-8h1a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-1");
}

.lz692cbkn {
  stroke-opacity: 0.4;
  d: path("M9 12h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
