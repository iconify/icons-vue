<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig8g-ub9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-receipt-slot" /></template>
<style>
.ig8g-ub9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19v4h-19Zm4 4v10a3 3 0 0 0 3 3H20a3 3 0 0 1-3-3v-10M9.5 11H14m-4.5 3.5H14");
}

</style>
