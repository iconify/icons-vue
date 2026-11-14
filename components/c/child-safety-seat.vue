<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wn-4q4bpq"/><path class="pg1c9_o9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:child-safety-seat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pg1c9_o9a {
  d: path("M8.25 6.5v6L11.5 15");
}

.wn-4q4bpq {
  d: path("M6.5 3H10a1.5 1.5 0 0 1 1.5 1.5v8H17a2 2 0 0 1 2 2v2a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 16.5v-12A1.5 1.5 0 0 1 6.5 3m-2 18h15");
}

</style>
