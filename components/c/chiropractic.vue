<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n5x8qtbrm"/><path class="ugt-67b9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chiropractic" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n5x8qtbrm {
  d: path("M6.75 2.5h3a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 9.75 6h-3A1.75 1.75 0 0 1 5 4.25A1.75 1.75 0 0 1 6.75 2.5M8 7.5h3a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 11 11H8a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 8 7.5m-.5 5h3a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 10.5 16h-3a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 7.5 12.5m-1.25 5h3A1.75 1.75 0 0 1 11 19.25A1.75 1.75 0 0 1 9.25 21h-3a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75M11.5 4.25l1.75.75m-.5 4.25l1.75.75m-2.25 4.25L14 15m-3 4.25l1.75.75M17.5 4.5c3.25 3.5 3.25 10.5 0 14");
}

.ugt-67b9k {
  d: path("M17.5 15.75v2.75h2.75");
}

</style>
