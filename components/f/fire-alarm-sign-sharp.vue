<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="fguu80nff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fire-alarm-sign-sharp" /></template>
<style>
.fguu80nff {
  d: path("M8.5 15v-3a3.5 3.5 0 0 1 7 0v3l1 1.25h-9Zm2.5 3.75h2M5.75 10a6 6 0 0 1 1.5-2.75m11 2.75a6 6 0 0 0-1.5-2.75");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
