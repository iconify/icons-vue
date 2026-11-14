<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c6pqxybel"/><path class="ws4oy3b7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kayak" /></template>
<style>
.c6pqxybel {
  d: path("M3.5 20.5C8 12 12 8 20.5 3.5C16 12 12 16 3.5 20.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ws4oy3b7b {
  d: path("M10.25 12a1.75 3.25 0 1 0 3.5 0a1.75 3.25 0 1 0-3.5 0Z");
}

</style>
