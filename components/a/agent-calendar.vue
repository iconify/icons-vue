<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cf9twjb7k"/><path class="ew4mtdb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:agent-calendar" /></template>
<style>
.cf9twjb7k {
  d: path("M12.467 21H3.5c-.6 0-1-.4-1-1c0-2.75 2.9-4.5 6.5-4.5c1.219 0 2.358.201 3.332.573M6.5 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.ew4mtdb0b {
  d: path("M4 11.5V9a5 5 0 0 1 10 0v1.5m-10 1c0 1.25.75 2 2.25 2m10.5 2h2.5A1.75 1.75 0 0 1 21 17.25v2.25a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.5v-2.25a1.75 1.75 0 0 1 1.75-1.75M15 17.75h6m-4.25-3.25V16m2.5-1.5V16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
