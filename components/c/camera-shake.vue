<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d3s87nkkx"/><path class="v3ls1_2dw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-shake" /></template>
<style>
.d3s87nkkx {
  d: path("M6 7.5h12V18H6Zm3.5 0l1-2h3l1 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v3ls1_2dw {
  d: path("M9.5 12.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM3 9.5V16m18-6.5V16");
}

</style>
