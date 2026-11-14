<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csmbnietv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boat-party" /></template>
<style>
.csmbnietv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14h18l-2.75 3.5H5.75Zm4.75-4h2.5A1.75 1.75 0 0 1 12 11.75v.5A1.75 1.75 0 0 1 10.25 14h-2.5A1.75 1.75 0 0 1 6 12.25v-.5A1.75 1.75 0 0 1 7.75 10M15 14V3.5m0 0L20.5 14m-17 6.5q2.25-1.25 4.5 0t4.5 0t4.5 0t3.5.25");
}

</style>
