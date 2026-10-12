<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="imzcb2bey"/><path class="dfcqmlbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bucket-list-sharp" /></template>
<style>
.dfcqmlbzj {
  d: path("M8.75 14.5L11 16.75l4.25-4.5");
}

.imzcb2bey {
  d: path("M5.5 8.25c0-4.25 3-5.5 6.5-5.5s6.5 1.25 6.5 5.5m-12.75 0h14l-.23 1.48l-1.54 10.04l-.23 1.48H6.25l-.23-1.48L4.48 9.73l-.23-1.48z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
