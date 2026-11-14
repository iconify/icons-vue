<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f8uwz1n7s"/><path class="be7uoob8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earth-hands" /></template>
<style>
.be7uoob8l {
  d: path("M9.25 9a2.75 6 0 1 0 5.5 0a2.75 6 0 1 0-5.5 0ZM6 9h12M2.5 10.5V14a6 6 0 0 0 6 6h2m11-9.5V14a6 6 0 0 1-6 6h-2");
}

.f8uwz1n7s {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
