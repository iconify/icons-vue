<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf560u8_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:composting-site" /></template>
<style>
.qf560u8_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21c0-4 2-6.5 5-6.5c.5-3 2.5-4.5 5-4.5s4.5 2 4.5 4c2.5 0 4.5 2.5 4.5 7ZM7 18h3m3.5-.5h3m-4-7.5V5m0 2c0-2.5 2-4.5 5-4.5c0 2.5-2 4.5-5 4.5");
}

</style>
