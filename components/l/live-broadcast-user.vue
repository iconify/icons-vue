<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkywp9b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-broadcast-user" /></template>
<style>
.wkywp9b3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0M5 21.5c0-4 3.25-6 7-6s7 2 7 6M7.75 3.75a6 6 0 0 0 0 8.5m8.5-8.5a6 6 0 0 1 0 8.5m-12-8.75a9 9 0 0 0 0 9m15.5-9a9 9 0 0 1 0 9");
}

</style>
