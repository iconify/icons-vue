<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvuy171ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:greek-letters" /></template>
<style>
.xvuy171ak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 19.5h3.5c-2.5-2-4-5-4-8.5S7 5 12 5s7.5 2.5 7.5 6s-1.5 6.5-4 8.5H19");
}

</style>
