<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtk8pv8kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-pump" /></template>
<style>
.dtk8pv8kh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h10m-5 0v4.5m-.75 0h1.5a1.75 1.75 0 0 1 1.75 1.75v10A1.75 1.75 0 0 1 12.75 21h-1.5a1.75 1.75 0 0 1-1.75-1.75v-10a1.75 1.75 0 0 1 1.75-1.75M5 21h14");
}

</style>
