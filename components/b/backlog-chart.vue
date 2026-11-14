<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szv2wnb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backlog-chart" /></template>
<style>
.szv2wnb0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3v17.5h9.2M6 17.25V13m3 4.25V9.5m3 7.75V5.5M15 16h7v1.5a1 1 0 0 0 0 2V21h-7v-1.5a1 1 0 0 0 0-2Z");
}

</style>
