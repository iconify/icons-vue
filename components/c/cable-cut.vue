<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo6upcb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-cut" /></template>
<style>
.xo6upcb0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 14.5h3A2.25 2.25 0 0 1 10 16.75A2.25 2.25 0 0 1 7.75 19h-3a2.25 2.25 0 0 1-2.25-2.25a2.25 2.25 0 0 1 2.25-2.25m11.5 0h3a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 19.25 19h-3A2.25 2.25 0 0 1 14 16.75a2.25 2.25 0 0 1 2.25-2.25M12 5v4M7 6.5l1.75 3.75M17 6.5l-1.75 3.75");
}

</style>
