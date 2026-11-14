<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6b7h890l"/><path class="sa7nwymsn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leave-bus" /></template>
<style>
.g6b7h890l {
  d: path("M6 2.5h4A3.5 3.5 0 0 1 13.5 6v9.5A3.5 3.5 0 0 1 10 19H6a3.5 3.5 0 0 1-3.5-3.5V6A3.5 3.5 0 0 1 6 2.5M2.5 9h11M5 19v2.5m6-2.5v2.5m5.25-15a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sa7nwymsn {
  d: path("m18.5 8.75l-1 6.25l-1.25 6.5M17.5 15l3 6.5");
}

</style>
