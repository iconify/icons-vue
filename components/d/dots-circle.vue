<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2wtb_onk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dots-circle" /></template>
<style>
.u2wtb_onk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 4a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0M17 6.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0M19.25 12a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0M17 17.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0M11.25 20a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0M5.5 17.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0M3.25 12a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0M5.5 6.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

</style>
