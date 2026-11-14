<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfh4-qbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drought-well-dry" /></template>
<style>
.qfh4-qbuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 7l9-4.5L21 7M6 5.5V14m12-8.5V14M3 14h18v6.5H3Zm9-11.5v6m-2 0h4l-.5 2.75h-3Z");
}

</style>
