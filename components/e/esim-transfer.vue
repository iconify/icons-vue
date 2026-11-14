<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t0o7ilb2i"/><path class="j4b-4km1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:esim-transfer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4b-4km1x {
  d: path("m15.5 5l2.5.5l.5-2.5");
}

.t0o7ilb2i {
  d: path("M5.125 8.5h1.75A2.625 2.625 0 0 1 9.5 11.125v7.75A2.625 2.625 0 0 1 6.875 21.5h-1.75A2.625 2.625 0 0 1 2.5 18.875v-7.75A2.625 2.625 0 0 1 5.125 8.5m12 0h1.75a2.625 2.625 0 0 1 2.625 2.625v7.75a2.625 2.625 0 0 1-2.625 2.625h-1.75a2.625 2.625 0 0 1-2.625-2.625v-7.75A2.625 2.625 0 0 1 17.125 8.5M6 5.5c2-3 10-3 12 0");
}

</style>
