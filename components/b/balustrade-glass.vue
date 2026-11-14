<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1tsormeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:balustrade-glass" /></template>
<style>
.q1tsormeb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21v-2.5h6v-3h6v-3h6V21ZM5.868 8.597l11-5.107A1.5 1.5 0 0 1 19 4.85v1.693a1.5 1.5 0 0 1-.868 1.36l-11 5.107A1.5 1.5 0 0 1 5 11.65V9.957a1.5 1.5 0 0 1 .868-1.36M5 14v4.5m14-11v5");
}

</style>
