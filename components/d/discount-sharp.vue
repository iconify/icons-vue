<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="q54osnf6n"/><path class="qjkwypbnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:discount-sharp" /></template>
<style>
.q54osnf6n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.75 3.41l.5.44l.76.66l.98-.19l.65-.13l.99-.2l.32.95l.21.63l.32.95l.95.32l.63.21l.95.33l-.2.98l-.13.65l-.19.98l.66.76l.44.5l.66.75l-.66.75l-.44.5l-.66.76l.19.98l.13.65l.2.99l-.95.32l-.63.21l-.95.32l-.32.95l-.21.63l-.32.95l-.99-.2l-.65-.13l-.98-.19l-.76.66l-.5.44l-.75.66l-.75-.66l-.5-.44l-.76-.66l-.98.19l-.65.13l-.98.2l-.33-.95l-.21-.63l-.32-.95l-.95-.32l-.63-.21l-.95-.32l.2-.99l.13-.65l.19-.98l-.66-.76l-.44-.5l-.66-.75l.66-.75l.44-.5l.66-.76l-.19-.98l-.13-.65l-.2-.99l.95-.32l.63-.21l.95-.32l.32-.95l.21-.63l.32-.95l.99.2l.65.13l.98.19l.76-.66l.5-.44l.75-.66zm-3.5 11.34l5.5-5.5");
}

.qjkwypbnm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 9.5h.01m4.99 5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
