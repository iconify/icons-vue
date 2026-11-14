<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn5f_ys5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:group-join" /></template>
<style>
.hn5f_ys5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c0-2.5 2.1-4.25 4.75-4.25S12 17.5 12 20c0 .6-.4 1-1 1H3.5c-.6 0-1-.4-1-1M4 9.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M13 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m.25 6.5c.65-.75 1.45-1.25 2.25-1.25c1.75 0 3.25.5 4.25 1.25M21 18h-6m2.5-2.5L15 18l2.5 2.5");
}

</style>
