<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mry-ye5tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coverage-improve" /></template>
<style>
.mry-ye5tz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 10.5h.01m3.172-3.182a4.5 4.5 0 0 1 0 6.364m-6.364 0a4.5 4.5 0 0 1 0-6.364M17.01 4.49q.192.192.371.395t.345.419q.166.214.317.439q.152.225.289.459t.259.476t.229.492q.106.249.196.505t.164.517q.073.261.13.526t.097.533q.04.269.062.539q.023.27.029.541q.005.271-.007.542t-.041.541t-.076.537q-.046.267-.109.531M4.99 16.51a8.5 8.5 0 0 1 0-12.02M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
