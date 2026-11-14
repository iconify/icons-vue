<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mi4cv9bko"/><path class="wfn-6-bht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eco-friendly-product" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mi4cv9bko {
  d: path("M4 2.5h16A1.5 1.5 0 0 1 21.5 4v1.5A1.5 1.5 0 0 1 20 7H4a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 4 2.5M4 7v12.5q0 1 1 1h14q1 0 1-1V7");
}

.wfn-6-bht {
  d: path("M7.5 17.75C7.5 13 10 10 16.5 10c0 5-3 7.75-9 7.75m0 0l4.25-4.25");
}

</style>
