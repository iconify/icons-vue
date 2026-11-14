<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2cimvq2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-pharmacy" /></template>
<style>
.f2cimvq2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.5h6.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 15.25 5h-6.5A1.25 1.25 0 0 1 7.5 3.75A1.25 1.25 0 0 1 8.75 2.5m.75 5.25h5a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 18v-6.75a3.5 3.5 0 0 1 3.5-3.5M12 11.5v6m-3-3h6");
}

</style>
