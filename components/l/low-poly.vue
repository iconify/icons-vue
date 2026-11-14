<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f1iyce6_y"/><path class="t-s9lw8qq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:low-poly" /></template>
<style>
.f1iyce6_y {
  d: path("m12 2.5l8.25 4.75v9.5L12 21.5l-8.25-4.75v-9.5Z");
}

.t-s9lw8qq {
  d: path("M3.75 7.25h16.5L12 21.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
