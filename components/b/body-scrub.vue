<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ibzv54bni"/><path class="qxl3ppb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:body-scrub" /></template>
<style>
.ibzv54bni {
  d: path("M3 12h18l-1.5 6.75a2.25 2.25 0 0 1-2.25 1.75H6.75a2.25 2.25 0 0 1-2.25-1.75Z");
}

.qxl3ppb4f {
  d: path("M7 7a5 5 0 1 0 10 0A5 5 0 1 0 7 7Zm5-1.5h.01M10.5 8.25h.01m2.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
