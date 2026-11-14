<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cw9kw7brk"/><path class="jw1ka6bka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-sandbox" /></template>
<style>
.cw9kw7brk {
  d: path("M3 12v6.5A2.5 2.5 0 0 0 5.5 21h13a2.5 2.5 0 0 0 2.5-2.5V12m-5.271-8.376l2.867 2.007m-1.434-1.003l-5.449 7.782");
}

.jw1ka6bka {
  d: path("m9.665 10.976l4.096 2.868l-2.581 3.686l-3.482.614l-.614-3.482Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
