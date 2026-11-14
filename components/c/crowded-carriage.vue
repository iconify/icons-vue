<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cv-p_rbhr"/><path class="qwturt7wh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crowded-carriage" /></template>
<style>
.cv-p_rbhr {
  d: path("M2.5 4h19v14.5h-19Z");
}

.qwturt7wh {
  d: path("M4.5 9A1.75 1.75 0 1 0 8 9a1.75 1.75 0 1 0-3.5 0Zm5.75 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM16 9a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 16 9ZM2.5 16.5a3.375 3.375 0 0 1 6.75 0a2.75 2.75 0 0 1 5.5 0a3.375 3.375 0 0 1 6.75 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
