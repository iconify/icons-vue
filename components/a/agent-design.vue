<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acr3-tq1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:agent-design" /></template>
<style>
.acr3-tq1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5q.75 6.75 7.5 7.5q-6.75.75-7.5 7.5q-.75-6.75-7.5-7.5q6.75-.75 7.5-7.5m5.375 17.125l.27-.991a1.5 1.5 0 0 1 .387-.666l2.718-2.718a1.414 1.414 0 0 1 2 0a1.414 1.414 0 0 1 0 2l-2.718 2.718a1.5 1.5 0 0 1-.666.387l-.991.27a.814.814 0 0 1-1-1m.375-1.375l2 2");
}

</style>
