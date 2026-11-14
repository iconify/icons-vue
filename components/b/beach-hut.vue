<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g3a0chbvk"/><path class="f_lq_nzmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beach-hut" /></template>
<style>
.f_lq_nzmc {
  d: path("M11.5 14.5h1A1.5 1.5 0 0 1 14 16v3a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 19v-3a1.5 1.5 0 0 1 1.5-1.5m-8 6.5h17");
}

.g3a0chbvk {
  d: path("m4 12l8-7.5l8 7.5Zm3 0h10a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 19v-5.5A1.5 1.5 0 0 1 7 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
