<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s5c-9172a"/><path class="x0576_bnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-changing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s5c-9172a {
  d: path("M3.75 4zA1.25 1.25 0 0 1 5 5.25v15a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25v-15A1.25 1.25 0 0 1 3.75 4m2.5 9.5h14a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 20.25 16h-14A1.25 1.25 0 0 1 5 14.75a1.25 1.25 0 0 1 1.25-1.25M5 20.5L15.5 16m-9-6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.x0576_bnk {
  d: path("M8.25 7.5c0-1 1.25-1.25 1.5-.5m3 6.5v-2c0-1.25.75-2 2-2H18c1.25 0 2 .75 2 2v2");
}

</style>
