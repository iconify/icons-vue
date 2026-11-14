<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjt61sy_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drone-landing" /></template>
<style>
.xjt61sy_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3v2.5h5m5 0h5V3m-17 0h4m11 0h4m-10.25.75h1.5A1.75 1.75 0 0 1 14.5 5.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 9.5 5.5a1.75 1.75 0 0 1 1.75-1.75M12 10v4.25M9.75 12L12 14.25L14.25 12M3.5 19.25a8.5 2.25 0 1 0 17 0a8.5 2.25 0 1 0-17 0");
}

</style>
