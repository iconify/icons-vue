<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quswun63e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flight-diversion" /></template>
<style>
.quswun63e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21.5V13q0-5.5 5.5-5.5h3.25m8.75 0c0 .75-.75 1-1.5 1h-2.25l-2.5 4h-1.5l1.5-4h-.75l-1 1.25h-.75v-4.5h.75l1 1.25h.75l-1.5-4h1.5l2.5 4H20c.75 0 1.5.25 1.5 1M4 5.5h.01M4 2.75h.01");
}

</style>
