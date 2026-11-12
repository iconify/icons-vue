<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i6_yopskj"/><path class="fupzn-bji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-rebase-duocolor" /></template>
<style>
.fupzn-bji {
  d: path("M3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0M17 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.i6_yopskj {
  stroke-opacity: 0.4;
  d: path("M5 8v8M7 6h10m2 15v-6a2 2 0 0 0-2-2h-6m3-3l-3 3l3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
