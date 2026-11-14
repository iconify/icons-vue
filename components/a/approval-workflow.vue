<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iq3ub5hzq"/><path class="iw0yty_0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:approval-workflow" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iq3ub5hzq {
  d: path("M5.125 4.5h1.25A2.625 2.625 0 0 1 9 7.125v2.25A2.625 2.625 0 0 1 6.375 12h-1.25A2.625 2.625 0 0 1 2.5 9.375v-2.25A2.625 2.625 0 0 1 5.125 4.5m12.5 0h1.25A2.625 2.625 0 0 1 21.5 7.125v2.25A2.625 2.625 0 0 1 18.875 12h-1.25A2.625 2.625 0 0 1 15 9.375v-2.25A2.625 2.625 0 0 1 17.625 4.5M9 8.25h6");
}

.iw0yty_0f {
  d: path("m13 6.25l2 2l-2 2M14.75 18l2 2L21 15.75");
}

</style>
