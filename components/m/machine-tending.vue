<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxrs9m50r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:machine-tending" /></template>
<style>
.dxrs9m50r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5h7m-3.5 0L9.5 8M7 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0h5.5V8m-2.25 2.5L17.5 8l2.25 2.5m-6.25 3v7h8v-7");
}

</style>
