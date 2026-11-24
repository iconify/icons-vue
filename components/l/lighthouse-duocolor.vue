<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="som-gobdx"/><path class="o0kaf7zae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lighthouse-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o0kaf7zae {
  d: path("M9 12h6l3 9H6zm-2 0h10m-8 0V8H8l4-4l4 4h-1v4M3 21h18M7 18l9-3");
}

.som-gobdx {
  stroke-opacity: 0.4;
  d: path("M3 9h2m14 0h2");
}

</style>
