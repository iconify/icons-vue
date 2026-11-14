<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6olv-hqu"/><path class="qfi76c80d"/><path class="pi_3pdbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:batch-transaction" /></template>
<style>
.e6olv-hqu {
  d: path("M6 10h6a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 12 20H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pi_3pdbah {
  d: path("M8.5 4h11a2 2 0 0 1 2 2v8M9 10v10");
}

.qfi76c80d {
  d: path("M5.5 7h11a2 2 0 0 1 2 2v8");
}

</style>
