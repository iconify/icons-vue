<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muv68xb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fasting" /></template>
<style>
.muv68xb2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 12a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0m-4.5-8.5v3a1.25 1.25 0 0 0 2.5 0v-3M4 7.75V20.5m15.5 0v-17c2 1.5 2 6.5 1.5 8.5h-1.5m-12 4.5l9-9");
}

</style>
