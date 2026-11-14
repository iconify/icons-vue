<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6qu-x1ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-auction" /></template>
<style>
.w6qu-x1ci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 4.964L17.036 8.5a2.5 2.5 0 0 1 0 3.536a2.5 2.5 0 0 1-3.536 0L9.964 8.5a2.5 2.5 0 0 1 0-3.536a2.5 2.5 0 0 1 3.536 0M3 19l8.75-8.75M14.5 20.5v-2.25l1.5-2.5h4.5l1.5 2.5v2.25Zm0-2.25H22");
}

</style>
