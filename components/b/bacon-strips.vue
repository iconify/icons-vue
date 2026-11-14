<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oir2izjum"/><path class="xovetrixx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bacon-strips" /></template>
<style>
.oir2izjum {
  d: path("M4 6q4-2.5 8 0t8 0v5q-4 2.5-8 0t-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xovetrixx {
  d: path("M4 14q4-2.5 8 0t8 0v5q-4 2.5-8 0t-8 0Z");
}

</style>
