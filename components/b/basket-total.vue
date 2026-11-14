<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pl3lktb9y"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basket-total" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.pl3lktb9y {
  d: path("M2.5 9.5h17M4 9.5l1.5 10h5.888m6.208-7.306L18 9.5m-11.5 0l2.75-6h3.5l2.75 6M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
