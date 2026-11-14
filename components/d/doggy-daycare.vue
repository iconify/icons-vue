<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frg_3ei7x"/><path class="x1f85abnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:doggy-daycare" /></template>
<style>
.frg_3ei7x {
  d: path("m4.759 12.478l6.25-4.296a1.75 1.75 0 0 1 1.982 0l6.25 4.296A1.75 1.75 0 0 1 20 13.921v5.329A1.75 1.75 0 0 1 18.25 21H5.75A1.75 1.75 0 0 1 4 19.25v-5.329a1.75 1.75 0 0 1 .759-1.443");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1f85abnr {
  d: path("M10 21v-3a2 2 0 0 1 4 0v3m-7.75-9.75a5.8 5.8 0 1 1 11.5 0m-13-5L3 5.25m16.25 1l1.75-1");
}

</style>
