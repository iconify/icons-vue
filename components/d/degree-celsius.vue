<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg3_qeb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:degree-celsius" /></template>
<style>
.pg3_qeb7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.25 7.75a6 6 0 1 0 0 8.5M5.5 3.75a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 1 1 0-4.5");
}

</style>
