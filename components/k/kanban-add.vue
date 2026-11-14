<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrwtm792q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kanban-add" /></template>
<style>
.mrwtm792q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h1.5A1.5 1.5 0 0 1 7 4.5v12A1.5 1.5 0 0 1 5.5 18H4a1.5 1.5 0 0 1-1.5-1.5v-12A1.5 1.5 0 0 1 4 3m7.25 0h1.5a1.5 1.5 0 0 1 1.5 1.5V12a1.5 1.5 0 0 1-1.5 1.5h-1.5a1.5 1.5 0 0 1-1.5-1.5V4.5a1.5 1.5 0 0 1 1.5-1.5m7.25 0H20a1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 20 10h-1.5A1.5 1.5 0 0 1 17 8.5v-4A1.5 1.5 0 0 1 18.5 3M18 15v6m-3-3h6");
}

</style>
