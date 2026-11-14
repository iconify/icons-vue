<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvmbwzb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:direct-deposit" /></template>
<style>
.mvmbwzb8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.75 6.25l3.435-2.223a1.5 1.5 0 0 1 1.63 0L16.25 6.25A1.495 1.495 0 0 1 15.438 9H8.562a1.495 1.495 0 0 1-.812-2.75M3.5 20.5h17M6 11.75v6m12-6v6m-6-6v6M9.25 15L12 17.75L14.75 15");
}

</style>
