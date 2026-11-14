<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qkzh9zbuh"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compliance-calendar" /></template>
<style>
.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.qkzh9zbuh {
  d: path("M13.8 21H3V4.5h18v7.3m0 7.9V21h-1.3M3 9.5h18m-13-7v4m8-4v4m-8.5 7h.01m4.49 0h.01m4.49 0h.01m-9.01 4h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
