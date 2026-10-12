<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="c_hs3p2zv"/><path class="nz2rpibzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kettlebell-sharp" /></template>
<style>
.c_hs3p2zv {
  d: path("M8.91 20.5a6.75 6.75 0 1 1 6.18 0Z");
}

.nz2rpibzy {
  d: path("M8 9.25V3h8v6.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
