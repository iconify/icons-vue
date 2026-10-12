<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ift8z5byc"/><path class="rccjqmmxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fertilizer-bag-sharp" /></template>
<style>
.ift8z5byc {
  d: path("M4.5 2.75h15v18.5h-15zm0 3.75h15");
}

.rccjqmmxf {
  d: path("M8.5 17.5c0-4.5 2.5-7.5 7-8c.25 4.75-2.25 7.75-7 8Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
