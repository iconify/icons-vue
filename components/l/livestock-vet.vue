<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5tnh1b8x"/><path class="u6vf1g6id"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:livestock-vet" /></template>
<style>
.d5tnh1b8x {
  d: path("M6.5 6H16v5.5H6.5V10H4a1.5 1.5 0 0 1-1.5-1.5V6L4 4.5h2.5ZM3.25 2.5l.75 2m3.25-2l-.75 2m1.5 7V17m4.5-5.5V17M16 6.5l2.25 3.75M15.5 14.5v1a2.75 2.75 0 0 0 5.5 0v-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u6vf1g6id {
  d: path("M16.75 19.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
