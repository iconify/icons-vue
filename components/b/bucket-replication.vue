<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qhr2pr76m"/><path class="w1_g04pxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bucket-replication" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qhr2pr76m {
  d: path("M2.5 5a8.5 2 0 1 0 17 0a8.5 2 0 1 0-17 0");
}

.w1_g04pxt {
  d: path("m2.5 5l2 14.5q3.54 1.089 7.079.992m7.029-9.026L19.5 5m-.75 12H20a1.75 1.75 0 0 1 1.75 1.75V20A1.75 1.75 0 0 1 20 21.75h-1.25A1.75 1.75 0 0 1 17 20v-1.25A1.75 1.75 0 0 1 18.75 17m-4.5 2.75v-4.5a1 1 0 0 1 1-1h4.5");
}

</style>
