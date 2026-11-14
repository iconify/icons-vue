<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sim0apbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-blow-pipe" /></template>
<style>
.sim0apbfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 17.5l6-6a1.414 1.414 0 0 1 2 0a1.414 1.414 0 0 1 0 2l-6 6a1.414 1.414 0 0 1-2 0a1.414 1.414 0 0 1 0-2m-1.75.25l3.5 3.5M18 2.5c2.25 2.25 3 4 3 6a3 3 0 0 1-6 0c0-2 .75-3.75 3-6");
}

</style>
