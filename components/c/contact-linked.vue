<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jigbqsb_d"/><path class="eioib5fst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contact-linked" /></template>
<style>
.eioib5fst {
  d: path("M10.5 16H18v4.5h-7.5Z");
}

.jigbqsb_d {
  d: path("M4.25 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 13a3.75 3.5 0 0 1 7.5 0m5.75-8.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM14 13a3.75 3.5 0 0 1 7.5 0m-16 3H13v4.5H5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
