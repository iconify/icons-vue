<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgx4dsb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:classical-portico" /></template>
<style>
.zgx4dsb0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 6l3.65-2.028a1.75 1.75 0 0 1 1.7 0L16.5 6a1.334 1.334 0 0 1-.648 2.5H8.148A1.334 1.334 0 0 1 7.5 6M3 20.5h18m-15.75-9h2.5m-1.25 0v6m4.25-6h2.5m-1.25 0v6m4.25-6h2.5m-1.25 0v6");
}

</style>
