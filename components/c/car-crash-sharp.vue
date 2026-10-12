<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wiks7-bop"/><circle class="gsab0-usu"/><circle class="qvvpj7kar"/><path class="d3wlpm0rg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-crash-sharp" /></template>
<style>
.d3wlpm0rg {
  d: path("m20.5 6.25l.75-1.75m0 5.75h-1m-3-4.5L16.75 4");
}

.gsab0-usu {
  cx: 6.75px;
  cy: 17.5px;
  r: 2.25px;
}

.qvvpj7kar {
  cx: 14.25px;
  cy: 17.5px;
  r: 2.25px;
}

.wiks7-bop {
  d: path("M2.75 16v-2.25l-.001-1.184L3.9 12.29l2.1-.54L8.3 8.8l.592-.79L9.88 8h3.37l.904.001l.596.679l2 2.32l1.5-.75l-.5 1.75l1.75.75L18 14l.75 1.5l1.48 1.598l-2.15-.348H2.75v-1Zm3.75-4h9m-4.25-2.5V12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
