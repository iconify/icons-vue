<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jta5xzb9q"/><path class="v7qoo6big"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bomb" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jta5xzb9q {
  d: path("M3.5 14a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

.v7qoo6big {
  d: path("M15.5 9c.5-1.25.75-2 1.5-2.5M19.75 2v3.5M18 3.75h3.5M6.741 12.632a4 4 0 0 1 2.391-2.391");
}

</style>
