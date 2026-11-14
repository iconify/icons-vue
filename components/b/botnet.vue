<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_hnobcrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:botnet" /></template>
<style>
.m_hnobcrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M2.5 2.5h5v5h-5Zm14 0h5v5h-5Zm-14 14h5v5h-5Zm14 0h5v5h-5Zm-9-9l2.25 2.25m4.5 0L16.5 7.5m-9 9l2.25-2.25m4.5 0l2.25 2.25");
}

</style>
