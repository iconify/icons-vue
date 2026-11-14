<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5r3y-bqy"/><path class="p85ya6b6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cart-check" /></template>
<style>
.d5r3y-bqy {
  d: path("M7.424 7h10.86a1.75 1.75 0 0 1 1.703 2.155l-.417 1.75a1.75 1.75 0 0 1-1.702 1.345h-4.243a1.375 1.375 0 0 0-1.375 1.375A1.375 1.375 0 0 1 10.875 15H8.409a1.75 1.75 0 0 1-1.71-1.376l-.984-4.5A1.75 1.75 0 0 1 7.424 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p85ya6b6q {
  d: path("M2.5 3.5h2L7 15m0 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m7.75-1l2 2L21 15.75");
}

</style>
