<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jlrrjwxbl"/><path class="wcrc9bbsn"/><circle class="jwdhipbso"/><path class="q_mj3bc9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:background-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlrrjwxbl {
  width: 12.5px;
  height: 17px;
  x: 3.75px;
  y: 2.75px;
  rx: 2px;
}

.jwdhipbso {
  cx: 16.25px;
  cy: 16.25px;
  r: 3.5px;
}

.q_mj3bc9y {
  d: path("m18.75 18.75l2.5 2.5");
}

.wcrc9bbsn {
  d: path("M11.75 7.5a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 1 1 3.5 0M7 13.25c.5-1.25 1.6-2 3-2s2.5.75 3 2");
}

</style>
