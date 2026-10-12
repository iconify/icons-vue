<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h36yrhb9k"/><rect class="bww1wacci"/><path class="c92gv4ess"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jharokha" /></template>
<style>
.bww1wacci {
  width: 13px;
  height: 9.5px;
  x: 5.5px;
  y: 6.5px;
  rx: 0.75px;
}

.c92gv4ess {
  d: path("M9 16v-3.5a3 3 0 0 1 6 0V16Zm-4.75 0h15.5M7.5 16c0 3 1 5 2.5 5.25M16.5 16c0 3-1 5-2.5 5.25");
}

.h36yrhb9k {
  d: path("M7.75 3h8.5q.75 0 1.3.51l2.65 2.48q.55.51-.2.51H4q-.75 0-.2-.51l2.65-2.48Q7 3 7.75 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
