<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o0sjnxbzj"/><path class="pd_u6ybei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:golden-ratio-sharp" /></template>
<style>
.o0sjnxbzj {
  d: path("M3 6h18v11H3zm11 0v11");
}

.pd_u6ybei {
  d: path("M6 17a8 8 0 0 1 8-8");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
