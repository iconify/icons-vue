<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rnbq9abgd"/><path class="fw980cc_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:employee-referral" /></template>
<style>
.fw980cc_t {
  d: path("M9.25 13.75h2a1.75 1.75 0 0 1 0 3.5h-2a1.75 1.75 0 0 1 0-3.5m3.5 0h2a1.75 1.75 0 0 1 0 3.5h-2a1.75 1.75 0 0 1 0-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnbq9abgd {
  d: path("M9.993 20.006q.007.243.007.494H2c0-4.09 1.446-6.941 3.399-7.426m13.19-.003C20.548 13.547 22 16.402 22 20.5h-8q0-.243.007-.48M3 6.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m12 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
