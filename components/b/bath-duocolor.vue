<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g8j-a8bir"/><path class="u9b-9843x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bath-duocolor" /></template>
<style>
.g8j-a8bir {
  stroke-opacity: 0.4;
  d: path("M5 12V6a2 2 0 1 1 4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u9b-9843x {
  d: path("M3 12h18M5 12v4a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2v-4M8 18v2m8-2v2");
}

</style>
