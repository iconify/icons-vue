<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="cducycw1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gfci-outlet" /></template>
<style>
.cducycw1i {
  d: path("M10.25 6.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m0 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-1.5-6.5h1A1.25 1.25 0 0 1 11 12a1.25 1.25 0 0 1-1.25 1.25h-1A1.25 1.25 0 0 1 7.5 12a1.25 1.25 0 0 1 1.25-1.25m5.5 0h1A1.25 1.25 0 0 1 16.5 12a1.25 1.25 0 0 1-1.25 1.25h-1A1.25 1.25 0 0 1 13 12a1.25 1.25 0 0 1 1.25-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o72zbacef {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5");
}

</style>
