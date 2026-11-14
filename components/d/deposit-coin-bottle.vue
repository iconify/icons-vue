<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wic1ecbkc"/><path class="ndzwabc2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-coin-bottle" /></template>
<style>
.ndzwabc2p {
  d: path("M11.5 2.5H13A2.25 2.25 0 0 1 13 7h-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wic1ecbkc {
  d: path("M10.25 9.75V12c0 1-2.25 1.5-2.25 3.5V20a1.5 1.5 0 0 0 1.5 1.5h5A1.5 1.5 0 0 0 16 20v-4.5c0-2-2.25-2.5-2.25-3.5V9.75m-4.5-5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

</style>
