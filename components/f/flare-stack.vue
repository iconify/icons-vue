<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qplf6-tcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flare-stack" /></template>
<style>
.qplf6-tcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 10.5h1A1.5 1.5 0 0 1 14 12v8a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 20v-8a1.5 1.5 0 0 1 1.5-1.5M6 21.5h12m-6-19c3.5 2.5 3 5 0 5s-3.5-2.5 0-5");
}

</style>
