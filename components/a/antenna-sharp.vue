<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="kx85uxbfn"/><path class="zkpdqqh1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:antenna-sharp" /></template>
<style>
.kx85uxbfn {
  cx: 12px;
  cy: 7.25px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zkpdqqh1g {
  d: path("M7.75 21.25L12 8.75l4.25 12.5m-6.75-5h5M8.52 9.69L6.809 7.25L8.52 4.81m-2.66 6.74a7.5 7.5 0 0 1 0-8.6m9.62 1.86l1.711 2.44l-1.711 2.44m2.66-6.74a7.5 7.5 0 0 1 0 8.6");
}

</style>
