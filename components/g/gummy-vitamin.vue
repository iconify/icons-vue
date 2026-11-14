<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l_w6d2zjv"/><path class="e9ldk6bcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gummy-vitamin" /></template>
<style>
.e9ldk6bcb {
  d: path("M9.75 13.5q0-2 1.75-2.75");
}

.l_w6d2zjv {
  d: path("m12 3l3.25 5L21 9.5l-3.75 4.75l.25 6L12 18l-5.5 2.25l.25-6L3 9.5L8.75 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
