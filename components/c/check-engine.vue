<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw6fhskpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:check-engine" /></template>
<style>
.zw6fhskpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 8.5H15q1 0 1.62.78l.76.94Q18 11 19 11h1.25q1 0 1 1v4.5q0 1-1 1H19q-1 0-1.62.78l-.76.94Q16 20 15 20H9q-1 0-1.68-.74l-1.39-1.52Q5.25 17 5.25 16V9.5q0-1 1-1M2.75 11v6m0-3h2.5m3-8.75h5.5m-2.75 0V8.5");
}

</style>
