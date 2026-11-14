<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o1lbe0b4b"/><path class="x8o_ol39y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bassoon" /></template>
<style>
.o1lbe0b4b {
  d: path("M9.25 21.5L10.5 18V5.25a1.75 1.75 0 0 1 3.5 0V18l1.25 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x8o_ol39y {
  d: path("M10.5 9C7.5 9 6 7.5 6 5L4.5 2.5");
}

</style>
