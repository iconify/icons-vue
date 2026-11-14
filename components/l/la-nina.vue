<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jof161qqk"/><path class="bi12wbokh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:la-nina" /></template>
<style>
.bi12wbokh {
  d: path("M3 9.5q2.25-2.5 4.5 0t4.5 0t4.5 0t4.5 0M3 14q2.25-2.5 4.5 0t4.5 0m6.5 1.5v6M16 17l5 3m-5 0l5-3");
}

.jof161qqk {
  d: path("M3 5q2.25-2.5 4.5 0T12 5t4.5 0T21 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
