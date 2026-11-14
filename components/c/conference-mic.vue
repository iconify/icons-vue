<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkd0plbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:conference-mic" /></template>
<style>
.xkd0plbuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21c0-2.5 2-3.5 4.5-3.5s4.5 1 4.5 3.5ZM9 17.5V14c0-3.25 2-5.25 5.25-5.5m4.975-4.975za1.75 1.75 0 0 1 0 2.475L16.75 8.475a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475l2.475-2.475a1.75 1.75 0 0 1 2.475 0");
}

</style>
