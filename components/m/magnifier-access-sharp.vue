<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="y-fd6pbmc"/><path class="vb9vl1bic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magnifier-access-sharp" /></template>
<style>
.vb9vl1bic {
  d: path("m15.75 15.75l5.5 5.5M7.5 13.5L10.25 7L13 13.5m-4.5-2.25H12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-fd6pbmc {
  cx: 10.25px;
  cy: 10.25px;
  r: 7.5px;
}

</style>
