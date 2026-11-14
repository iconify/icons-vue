<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l787i-wti"/><path class="cnrd28bff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hiring-manager" /></template>
<style>
.cnrd28bff {
  d: path("M9 15.25za.894.894 0 0 1 .88.739l.484 2.742a1.5 1.5 0 0 1-.416 1.321l-.198.198a1.06 1.06 0 0 1-1.5 0l-.198-.198a1.5 1.5 0 0 1-.416-1.321l.484-2.742A.894.894 0 0 1 9 15.25M15 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m4.25 1.75L21.5 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l787i-wti {
  d: path("M2.5 20c0-2.75 2.9-4.75 6.5-4.75s6.5 2 6.5 4.75c0 .6-.4 1-1 1h-11c-.6 0-1-.4-1-1M5.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
