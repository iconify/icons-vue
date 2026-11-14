<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na8vsfj3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-office-room" /></template>
<style>
.na8vsfj3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 3h4.75A2.625 2.625 0 0 1 13.5 5.625v1.75A2.625 2.625 0 0 1 10.875 10h-4.75A2.625 2.625 0 0 1 3.5 7.375v-1.75A2.625 2.625 0 0 1 6.125 3M3 21.5v-9h11.5v9M21 8v8h-3.5m-9-6v2.5M19.25 16v5.5");
}

</style>
