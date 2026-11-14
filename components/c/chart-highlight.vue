<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0empjbpu"/><path class="f8kb0lkfe"/><path class="j3tajacuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-highlight" /></template>
<style>
.a0empjbpu {
  d: path("M4.25 11za1.5 1.5 0 0 1 1.5 1.5v7a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-7a1.5 1.5 0 0 1 1.5-1.5m5.5-5za1.5 1.5 0 0 1 1.5 1.5v12a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-12A1.5 1.5 0 0 1 9.75 6");
}

.f8kb0lkfe {
  fill: currentColor;
  d: path("M15.25 3za1.5 1.5 0 0 1 1.5 1.5v15a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-15a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3tajacuf {
  d: path("M20.5 9za1.25 1.25 0 0 1 1.25 1.25v9.5A1.25 1.25 0 0 1 20.5 21a1.25 1.25 0 0 1-1.25-1.25v-9.5A1.25 1.25 0 0 1 20.5 9");
}

</style>
