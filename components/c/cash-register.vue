<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jxjx5bcer"/><path class="nnw_6cb2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cash-register" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jxjx5bcer {
  d: path("M6.188 3h3.625A2.19 2.19 0 0 1 12 5.188v.125A2.19 2.19 0 0 1 9.813 7.5H6.188A2.19 2.19 0 0 1 4 5.313v-.125A2.19 2.19 0 0 1 6.188 3M8 7.5V10m-1.412 0h10.824a2.625 2.625 0 0 1 2.558 2.035l.288 1.25A2.625 2.625 0 0 1 17.7 16.5H6.3a2.625 2.625 0 0 1-2.558-3.215l.288-1.25A2.625 2.625 0 0 1 6.588 10");
}

.nnw_6cb2c {
  d: path("M3 16.5v3A1.5 1.5 0 0 0 4.5 21h15a1.5 1.5 0 0 0 1.5-1.5v-3M8 13.25h.01m3.99 0h.01m3.99 0h.01");
}

</style>
