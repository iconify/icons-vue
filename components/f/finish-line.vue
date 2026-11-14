<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5m-51bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:finish-line" /></template>
<style>
.h5m-51bbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.5V3M2.5 21.5h5m11.5 0V3m-2.5 18.5h5M5 9q7 3.5 14 0M6.631 3.634l.619.241a.939.939 0 0 1 0 1.75l-.619.241A1.197 1.197 0 0 1 5 4.75a1.197 1.197 0 0 1 1.631-1.116");
}

</style>
