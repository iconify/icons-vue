<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk40jz_ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-valuation" /></template>
<style>
.gk40jz_ad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 10.5V7a3.5 3.5 0 0 1 7 0v3.5m-5.625 0h4.25a4.375 4.375 0 0 1 4.375 4.375v2.25a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 2.5 17.125v-2.25A4.375 4.375 0 0 1 6.875 10.5M18 9.5h1.5A1.5 1.5 0 0 1 21 11v3.379a1.5 1.5 0 0 1-.439 1.06l-.75.75a1.5 1.5 0 0 1-2.122 0l-.75-.75a1.5 1.5 0 0 1-.439-1.06V11A1.5 1.5 0 0 1 18 9.5m-5.75-4.25L16.5 9.5m2.25 2.5h.01M9 16h.01");
}

</style>
