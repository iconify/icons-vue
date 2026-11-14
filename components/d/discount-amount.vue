<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yy00elr_j"/><path class="cvdorzbhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discount-amount" /></template>
<style>
.cvdorzbhn {
  d: path("M5.25 6.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM10 13.5h5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yy00elr_j {
  d: path("M2.5 2.5H11l10.25 10.25l-8.5 8.5L2.5 11Z");
}

</style>
