<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="vwv921b0x"/><path class="x1mndibql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gym-sharp" /></template>
<style>
.vwv921b0x {
  cx: 12px;
  cy: 6.75px;
  r: 2px;
}

.x1mndibql {
  d: path("M10.5 11.25L9.25 15m4.25-3.75L14.75 15m-8 0h10.5M3.5 12.75h1.25V11h2v8h-2v-1.75h-2v-4.5zm17 0h-1.25V11h-2v8h2v-1.75h2v-4.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
