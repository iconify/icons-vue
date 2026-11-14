<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_86l4l2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-rca" /></template>
<style>
.d_86l4l2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5v2m-.5 0h1A1.5 1.5 0 0 1 9 6v1a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 5 7V6a1.5 1.5 0 0 1 1.5-1.5m.5 4zA2.5 2.5 0 0 1 9.5 11v2A2.5 2.5 0 0 1 7 15.5A2.5 2.5 0 0 1 4.5 13v-2A2.5 2.5 0 0 1 7 8.5m0 7v6m10-19v2m-.5 0h1A1.5 1.5 0 0 1 19 6v1a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 15 7V6a1.5 1.5 0 0 1 1.5-1.5m.5 4za2.5 2.5 0 0 1 2.5 2.5v2a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1-2.5-2.5v-2A2.5 2.5 0 0 1 17 8.5m0 7v6");
}

</style>
