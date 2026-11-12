<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="goey8jbow"/><path class="idh8r4wpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-merge-conflict-duocolor" /></template>
<style>
.goey8jbow {
  stroke-opacity: 0.4;
  d: path("M5 8a4 4 0 0 0 4 4h4m4-2l4 4m0-4l-4 4");
}

.idh8r4wpv {
  d: path("M3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0M5 8v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
