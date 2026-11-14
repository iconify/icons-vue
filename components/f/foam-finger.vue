<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wber1_b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:foam-finger" /></template>
<style>
.wber1_b_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 10V5a2.5 2.5 0 0 1 5 0v5h3a2.5 2.5 0 0 1 2.5 2.5V15a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 15v-2.5A2.5 2.5 0 0 1 7.5 10Zm.25 7.5h6.5A1.75 1.75 0 0 1 17 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75M13.5 10v4");
}

</style>
