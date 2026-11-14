<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o2csh_b0k"/><path class="bkt8m0bkt"/><path class="hsfhm_bqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-type-switch" /></template>
<style>
.bkt8m0bkt {
  fill: currentColor;
  d: path("M5.5 20.5V11H8v9.5Zm4.25 0V5h1.5v15.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hsfhm_bqu {
  d: path("M14.5 16H21m-1.75-1.75L21 16l-1.75 1.75M21.5 20H15m1.75-1.75L15 20l1.75 1.75");
}

.o2csh_b0k {
  d: path("M3.5 3v17.5h8.7");
}

</style>
