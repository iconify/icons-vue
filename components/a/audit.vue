<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q_p91qmvs"/><rect class="s8e5_8bzb"/><path class="olk1cqb8t"/><circle class="wfqdf5kbq"/><path class="xis7zt0ek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olk1cqb8t {
  d: path("M8.25 10h2.5m-2.5 3.25h2.5");
}

.q_p91qmvs {
  d: path("M9.5 21.25H7.25a2.5 2.5 0 0 1-2.5-2.5v-12a2.5 2.5 0 0 1 2.5-2.5h1.5m6.5 0h1.5a2.5 2.5 0 0 1 2.5 2.5V9.5");
}

.s8e5_8bzb {
  width: 6.5px;
  height: 3.5px;
  x: 8.75px;
  y: 2.75px;
  rx: 1.25px;
}

.wfqdf5kbq {
  cx: 15.75px;
  cy: 15.75px;
  r: 3px;
}

.xis7zt0ek {
  d: path("m18 18l3 3");
}

</style>
