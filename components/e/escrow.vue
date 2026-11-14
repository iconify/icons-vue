<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="la4nckwlf"/><path class="s1gyzwksf"/><path class="cvnda3kco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:escrow" /></template>
<style>
.cvnda3kco {
  d: path("M13.5 13.5q-.375-.75-1.5-.75c-1 0-1.5.5-1.5 1.25c0 1.5 3 .5 3 2c0 .75-.5 1.25-1.5 1.25q-1.125 0-1.5-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.la4nckwlf {
  d: path("M7.375 8h9.25A4.375 4.375 0 0 1 21 12.375v5.25A4.375 4.375 0 0 1 16.625 22h-9.25A4.375 4.375 0 0 1 3 17.625v-5.25A4.375 4.375 0 0 1 7.375 8M7.5 8V6.5a4.5 4.5 0 0 1 9 0V8");
}

.s1gyzwksf {
  d: path("M8 15a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
