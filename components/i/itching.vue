<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2_i967ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:itching" /></template>
<style>
.g2_i967ak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.25L12 10c1 0 1.75-.25 2.5-.75L17.25 8c.75-.25 1.5.5 1 1.25l-.5.5H20c.9 0 1.5.65 1.5 1.5V14c0 1-.75 1.75-1.75 1.75H13.5c-.75 0-1.25-.25-2-.5l-9 .5m15.25-3h3.75M4.5 3l2 3.5M8 3l2 3.5M11.5 3l2 3.5");
}

</style>
