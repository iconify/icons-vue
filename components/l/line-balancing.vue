<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv8n1_bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:line-balancing" /></template>
<style>
.dv8n1_bhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18m-9 0v9.5m-4 0h8M5.75 5.5h2A1.75 1.75 0 0 1 9.5 7.25v2A1.75 1.75 0 0 1 7.75 11h-2A1.75 1.75 0 0 1 4 9.25v-2A1.75 1.75 0 0 1 5.75 5.5m10.5 0h2A1.75 1.75 0 0 1 20 7.25v2A1.75 1.75 0 0 1 18.25 11h-2a1.75 1.75 0 0 1-1.75-1.75v-2a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
