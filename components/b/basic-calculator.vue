<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="bdn1f3bxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basic-calculator" /></template>
<style>
.bdn1f3bxy {
  d: path("M9.25 5.5h5.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 14.75 9h-5.5A1.75 1.75 0 0 1 7.5 7.25A1.75 1.75 0 0 1 9.25 5.5M9 12h.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 14v-.5A1.5 1.5 0 0 1 9 12m5.5 0h.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-.5A1.5 1.5 0 0 1 13 14v-.5a1.5 1.5 0 0 1 1.5-1.5m-6 5H10a1 1 0 0 1 1 1a1 1 0 0 1-1 1H8.5a1 1 0 0 1-1-1a1 1 0 0 1 1-1m5.5 0h1.5a1 1 0 0 1 1 1a1 1 0 0 1-1 1H14a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
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
