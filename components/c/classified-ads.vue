<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7n_je64o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:classified-ads" /></template>
<style>
.v7n_je64o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9v10a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 3 19V9zV3.5h14.5V18a2.5 2.5 0 0 1-2.5 2.5H4.5M9 7.5h8.5M9 12h3m2.75 0h2.75M9 16.5h3m2.75 0h2.75");
}

</style>
