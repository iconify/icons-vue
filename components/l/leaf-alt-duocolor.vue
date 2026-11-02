<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h38a9ebel"/><path class="jzf08gbjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-alt-duocolor" /></template>
<style>
.h38a9ebel {
  stroke-opacity: 0.4;
  d: path("M5 21c.1-.7.4-1.8 1-3m0 0c1.5-3 3-6 6-7");
}

.jzf08gbjp {
  d: path("M9 18c6.22 0 10.5-3.29 11-12V4h-4C7 4 4 8 4 13c0 1 0 3 2 5z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
