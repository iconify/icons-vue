<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yezwx4bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cutlery-set" /></template>
<style>
.yezwx4bwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5v4a2.75 2.75 0 0 0 5.5 0v-4M5.25 9.25V21.5m5.75 0v-19C13.5 4 13.5 9 13.5 12H11m5.5-6A2.25 3.5 0 1 0 21 6a2.25 3.5 0 1 0-4.5 0m2.25 3.5v12");
}

</style>
