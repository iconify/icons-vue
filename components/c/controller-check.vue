<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qgjz8bbrg"/><path class="em01dkqrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:controller-check" /></template>
<style>
.em01dkqrp {
  d: path("M14.75 10a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m0 8l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qgjz8bbrg {
  d: path("M13.583 15.5H8c-.75 1.25-1.5 2-2.75 2c-1.5 0-2.75-1.25-2.75-3V10c0-3.25 2-5.5 5-5.5h9c3 0 5 2.25 5 5.5v2.973M5.5 10H9M7.25 8.25v3.5");
}

</style>
