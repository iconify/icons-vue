<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="hz9voaclr"/><path class="k_j-l-bqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-station-sign-sharp" /></template>
<style>
.hz9voaclr {
  d: path("M6 18V6h7.75v12M5 18h9.75m-1-7.5h2.5v6.25h2.5V9l-1.5-1.5");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.k_j-l-bqs {
  d: path("M8.5 8.5h2.75V11H8.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
