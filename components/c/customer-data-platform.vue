<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l5k_heu7p"/><path class="r81-wq2_p"/><path class="d7oty2bkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:customer-data-platform" /></template>
<style>
.d7oty2bkn {
  d: path("M15 11.25a3.25 1.75 0 0 0 6.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5k_heu7p {
  d: path("M4.75 9a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M2.5 21c0-3.5 2.5-6 5.5-6s5.5 2.5 5.5 6M15 5a3.25 1.75 0 1 0 6.5 0A3.25 1.75 0 1 0 15 5");
}

.r81-wq2_p {
  d: path("M15 5v12.5a3.25 1.75 0 0 0 6.5 0V5");
}

</style>
