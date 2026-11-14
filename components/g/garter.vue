<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ffizkul3l"/><path class="y2ce11bna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garter" /></template>
<style>
.ffizkul3l {
  d: path("M2.5 14.5a9.5 6 0 1 0 19 0a9.5 6 0 1 0-19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y2ce11bna {
  d: path("M6 14.5a6 3 0 1 0 12 0a6 3 0 1 0-12 0Zm6-6l-3.5-5l-1 3Zm0 0l3.5-5l1 3Z");
}

</style>
