<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q31_rmbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:belayer" /></template>
<style>
.q31_rmbbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3 21.5c0-4 2.5-7 6-7s6 3 6 7m2.75-7.5h.5a3.75 3.75 0 0 1 0 7.5h-.5m0 0V17");
}

</style>
