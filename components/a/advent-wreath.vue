<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="os5d6opjy"/><path class="c5cqsz7gy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:advent-wreath" /></template>
<style>
.c5cqsz7gy {
  d: path("M4.25 9.5za1.25 1.25 0 0 1 1.25 1.25v2A1.25 1.25 0 0 1 4.25 14A1.25 1.25 0 0 1 3 12.75v-2A1.25 1.25 0 0 1 4.25 9.5M9.375 8zA1.125 1.125 0 0 1 10.5 9.125v2.5a1.125 1.125 0 0 1-1.125 1.125a1.125 1.125 0 0 1-1.125-1.125v-2.5A1.125 1.125 0 0 1 9.375 8m5.25 0za1.125 1.125 0 0 1 1.125 1.125v2.5a1.125 1.125 0 0 1-1.125 1.125a1.125 1.125 0 0 1-1.125-1.125v-2.5A1.125 1.125 0 0 1 14.625 8m5.125 1.5zA1.25 1.25 0 0 1 21 10.75v2A1.25 1.25 0 0 1 19.75 14a1.25 1.25 0 0 1-1.25-1.25v-2a1.25 1.25 0 0 1 1.25-1.25M4.25 6.75h.01m5.24-1.5h.01m4.99 0h.01m5.24 1.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.os5d6opjy {
  d: path("M2.5 16a9.5 3.5 0 1 0 19 0a9.5 3.5 0 1 0-19 0");
}

</style>
