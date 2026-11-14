<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoughrbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hazard-gas-pressure" /></template>
<style>
.uoughrbfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20v-7.5a4.5 4.5 0 0 1 9 0V20a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1M8.5 8V3m-2 0h4m-2 2.5h5.75m0 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m3.5 0L19 4.25");
}

</style>
