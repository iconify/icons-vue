<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ejco7teid"/><path class="rhlwb5bxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:altar-candles" /></template>
<style>
.ejco7teid {
  d: path("M3.5 17.5v-7a8.5 8.5 0 0 1 17 0v7m-17 0h17M2.5 21h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rhlwb5bxa {
  d: path("M7 17.5V13a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v4.5M8.5 6c1.25 1.25 1.5 2.25 0 3.25c-1.5-1-1.25-2 0-3.25M14 17.5V13a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v4.5M15.5 6c1.25 1.25 1.5 2.25 0 3.25c-1.5-1-1.25-2 0-3.25");
}

</style>
