<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kjjgjvbpo"/><path class="o25klbbjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:low-key" /></template>
<style>
.kjjgjvbpo {
  fill: currentColor;
  d: path("M4.5 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.o25klbbjj {
  d: path("M15.949 4.218a9.5 9.5 0 0 1 0 15.564");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
