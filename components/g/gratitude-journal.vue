<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qxocr3buf"/><path class="ia5jmun7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gratitude-journal" /></template>
<style>
.ia5jmun7n {
  d: path("M13.75 15s-3.25-2-3.25-4.25c0-.75.75-1.75 1.75-1.75c.5 0 1.25.5 1.5 1c.25-.5 1-1 1.5-1c1 0 1.75 1 1.75 1.75C17 13 13.75 15 13.75 15Z");
}

.qxocr3buf {
  d: path("M5 2.5h14v19H5Zm3.5 0v19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
