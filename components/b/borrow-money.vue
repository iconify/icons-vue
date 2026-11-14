<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoih8kb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:borrow-money" /></template>
<style>
.eoih8kb2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 6l3.772-2.095a1.5 1.5 0 0 1 1.456 0L16.5 6a1.334 1.334 0 0 1-.648 2.5H8.148A1.334 1.334 0 0 1 7.5 6M3 19.5h10.8m-8.3-8v5m4-5v5m4-5v5m5.5-2.25v7m-2.5-2.5l2.5 2.5l2.5-2.5");
}

</style>
