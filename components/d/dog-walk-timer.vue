<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u8w-kjlrm"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-walk-timer" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.u8w-kjlrm {
  d: path("M11 11c-5-4-5-8.5 0-8.5S16 7 11 11Zm0 0c0 3.5-2.5 4-4 6m-2.5 0H9v4.5H4.5Zm10.25 1a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
