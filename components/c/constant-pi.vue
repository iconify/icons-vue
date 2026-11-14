<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c2a3fh_2u"/><path class="jnl5_bc4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:constant-pi" /></template>
<style>
.c2a3fh_2u {
  d: path("M3.5 7q1-2.5 3.5-2.5h13.5m-11 0L7.5 20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnl5_bc4s {
  d: path("M15.5 4.5V17a3 3 0 0 0 3 3h1");
}

</style>
