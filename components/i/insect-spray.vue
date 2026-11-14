<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_fhsacnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insect-spray" /></template>
<style>
.t_fhsacnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10.5h2a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18v-4A3.5 3.5 0 0 1 8 10.5m-1 0V9a1 1 0 0 1 1-1h2.5a1 1 0 0 1 1 1v1.5m-2.25-6za1.5 1.5 0 0 1 1.5 1.5v.5A1.5 1.5 0 0 1 9.25 8a1.5 1.5 0 0 1-1.5-1.5V6a1.5 1.5 0 0 1 1.5-1.5m6.75-1l3.5-1m-3 3.75h4M16 9l3.5 1");
}

</style>
