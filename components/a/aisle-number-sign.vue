<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ib3epmbgp"/><path class="d6m66vbww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aisle-number-sign" /></template>
<style>
.d6m66vbww {
  d: path("M14.75 9h-4.5l-.5 3.75c.75-.5 1.5-.75 2.5-.75c1.75 0 3 1.25 3 3s-1.5 3-3.25 3c-1.25 0-2.25-.5-2.75-1.5M5.5 9h.01M18.5 9h.01");
}

.ib3epmbgp {
  d: path("M2.5 2.5h19M7 2.5V6m10-3.5V6M2.5 6h19v15h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
