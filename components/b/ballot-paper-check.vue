<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="tq-_nbcgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ballot-paper-check" /></template>
<style>
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

.tq-_nbcgv {
  d: path("M9.5 5.5h5a1.75 1.75 0 0 1 1.75 1.75v5A1.75 1.75 0 0 1 14.5 14h-5a1.75 1.75 0 0 1-1.75-1.75v-5A1.75 1.75 0 0 1 9.5 5.5m.75 2.5l3.5 3.5m0-3.5l-3.5 3.5m-2.5 6h8.5");
}

</style>
