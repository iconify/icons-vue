<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bonwwjblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dory" /></template>
<style>
.bonwwjblq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h18.5q-2 6.5-8 6.5H5Zm13-5L8.25 17M6 19a1.25 2.25 0 1 0 2.5 0A1.25 2.25 0 1 0 6 19");
}

</style>
