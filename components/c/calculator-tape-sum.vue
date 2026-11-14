<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzw57790p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:calculator-tape-sum" /></template>
<style>
.nzw57790p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10h8a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18v-4.5A3.5 3.5 0 0 1 8 10m-.5 0V2.5h9V10m-6.25-4h3.5m-5.5 8h.01M12 14h.01m3.74 0h.01m-7.51 4h.01M12 18h.01m3.74 0h.01");
}

</style>
