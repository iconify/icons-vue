<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bzr1dpb5e"/><path class="r3lvp8bvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airline-meal-tray" /></template>
<style>
.bzr1dpb5e {
  d: path("M6.875 4h10.25A4.375 4.375 0 0 1 21.5 8.375v7.25A4.375 4.375 0 0 1 17.125 20H6.875A4.375 4.375 0 0 1 2.5 15.625v-7.25A4.375 4.375 0 0 1 6.875 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3lvp8bvg {
  d: path("M5.5 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0m8.75-2.5h4.5m-4.5 0a2.25 2.25 0 0 1 4.5 0m-2.25 3za1.482 1.482 0 0 1 1.462 1.726l-.298 1.788A1.18 1.18 0 0 1 16.5 17a1.18 1.18 0 0 1-1.164-.986l-.298-1.788A1.482 1.482 0 0 1 16.5 12.5");
}

</style>
