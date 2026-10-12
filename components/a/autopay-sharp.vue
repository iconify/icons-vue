<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="drmrwvbgh"/><path class="uy1khubuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:autopay-sharp" /></template>
<style>
.drmrwvbgh {
  cx: 10px;
  cy: 14.25px;
  r: 6.75px;
}

.uy1khubuk {
  d: path("m11.81 12.79l-.435-1.08H8.39v1.33c0 1.77 3.56.99 3.56 2.88v1.36H8.77l-.54-1.08M20.5 2.75l-2.75 3.5H21L18.75 9.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
