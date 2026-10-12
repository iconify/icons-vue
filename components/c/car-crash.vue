<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrkyodb6w"/><circle class="gsab0-usu"/><circle class="qvvpj7kar"/><path class="d3wlpm0rg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-crash" /></template>
<style>
.d3wlpm0rg {
  d: path("m20.5 6.25l.75-1.75m0 5.75h-1m-3-4.5L16.75 4");
}

.gsab0-usu {
  cx: 6.75px;
  cy: 17.5px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrkyodb6w {
  d: path("M2.75 16v-2.25a1.5 1.5 0 0 1 1.15-1.46l2.1-.54L8.3 8.8A2 2 0 0 1 9.88 8h3.37a2 2 0 0 1 1.5.68l2 2.32l1.5-.75l-.5 1.75l1.75.75L18 14l.75 1.5a.75.75 0 0 1-.67 1.25H3.75a1 1 0 0 1-1-1Zm3.75-4h9m-4.25-2.5V12");
}

.qvvpj7kar {
  cx: 14.25px;
  cy: 17.5px;
  r: 2.25px;
}

</style>
