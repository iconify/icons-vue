<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvy0_ub4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-governance" /></template>
<style>
.qvy0_ub4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.75 6.5l3.489-2.053a1.5 1.5 0 0 1 1.522 0L16.25 6.5a1.343 1.343 0 0 1-.681 2.5H8.431a1.343 1.343 0 0 1-.681-2.5m-1.25 5v6m5.5-6v6m5.5-6v6m-14 3h17");
}

</style>
