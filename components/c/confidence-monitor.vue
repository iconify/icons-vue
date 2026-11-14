<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wfarjnz1d"/><path class="anil3kb_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:confidence-monitor" /></template>
<style>
.anil3kb_g {
  d: path("M7.75 6.75h8.5l1.25 5.5h-11ZM9.5 15L8 20.5m6.5-5.5l1.5 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wfarjnz1d {
  d: path("M5 4h14l2 11H3ZM3 20.5h18");
}

</style>
