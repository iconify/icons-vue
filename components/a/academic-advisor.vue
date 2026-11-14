<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="er5xfno9t"/><path class="tugom2bbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:academic-advisor" /></template>
<style>
.er5xfno9t {
  d: path("M3.5 6L12 2.5L20.5 6L12 9.5Z");
}

.tugom2bbj {
  d: path("M7.75 7.75V11a4.25 4.25 0 0 0 8.5 0V7.75M4.5 21.5c0-2 3.25-3.5 7.5-3.5s7.5 1.5 7.5 3.5m1-15.5v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
