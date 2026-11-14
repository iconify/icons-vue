<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1qz1bbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hotel-sign" /></template>
<style>
.c1qz1bbjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h10A3.5 3.5 0 0 1 20.5 7v5a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 12V7A3.5 3.5 0 0 1 7 3.5m1 12V21m8-5.5V21M9.5 6.75v5.5m5-5.5v5.5m-5-2.75h5");
}

</style>
