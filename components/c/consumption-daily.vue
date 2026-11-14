<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uavlymb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consumption-daily" /></template>
<style>
.uavlymb8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v18h8.75M6 17.5V12m2.75 5.5V7m2.75 10.5V10m3 5H22v6.5h-7.5Zm0 2.75H22m-5.25-4.25V16m3-2.5V16");
}

</style>
