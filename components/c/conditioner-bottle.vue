<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0v5xwgaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:conditioner-bottle" /></template>
<style>
.l0v5xwgaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8h3a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 4 18v-6.5A3.5 3.5 0 0 1 7.5 8m.25-4.5h2.5A1.75 1.75 0 0 1 12 5.25v1A1.75 1.75 0 0 1 10.25 8h-2.5A1.75 1.75 0 0 1 6 6.25v-1A1.75 1.75 0 0 1 7.75 3.5m4.25 2h4m-12 7h10M4 17h10m5-9s2 2.5 2 3.75a2 2 0 0 1-4 0C17 10.5 19 8 19 8");
}

</style>
