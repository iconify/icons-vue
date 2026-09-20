<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q6kjd1w_g"/><path class="u70k4y_qc"/><path class="fevuzkbbx"/><path class="bfcwd7bcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:escalate-human-outline-thin" /></template>
<style>
.bfcwd7bcm {
  d: path("M13 13a4 4 0 0 1 8 0");
}

.fevuzkbbx {
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q6kjd1w_g {
  d: path("M7.5 13.83a3.5 3.5 0 1 1 -2.96 0");
}

.u70k4y_qc {
  d: path("m9 15 5 -5");
}

</style>
