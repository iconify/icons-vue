<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d8rqq5b1x"/><path class="yqlj8ujbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:goalkeeper" /></template>
<style>
.d8rqq5b1x {
  d: path("M9.75 9.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yqlj8ujbt {
  d: path("M4.75 9.5L9 14.25h6l4.25-4.75M9 14.25v7.25m6-7.25v7.25M2.5 9.5V5.25a2.25 2.25 0 0 1 4.5 0V9.5Zm14.5 0V5.25a2.25 2.25 0 0 1 4.5 0V9.5Z");
}

</style>
