<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nlycgnwiq"/><path class="i3gtxibvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-medium-format" /></template>
<style>
.i3gtxibvy {
  d: path("M10 14.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.nlycgnwiq {
  d: path("M2.5 8.5h19V21h-19Zm2-5.5h7v5.5h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
