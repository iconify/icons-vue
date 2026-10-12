<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="m0ydh5bsj"/><circle class="mtl-gzbxy"/><circle class="fk_szrbck"/><path class="nswhppbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-pull-request-x" /></template>
<style>
.fk_szrbck {
  cx: 17.25px;
  cy: 18.75px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m0ydh5bsj {
  cx: 6.75px;
  cy: 5.25px;
  r: 2.25px;
}

.mtl-gzbxy {
  cx: 6.75px;
  cy: 18.75px;
  r: 2.25px;
}

.nswhppbyy {
  d: path("M6.75 7.5v9m10.5 0V8.75a2.5 2.5 0 0 0-2.5-2.5H12m2.5-2.5L12 6.25l2.5 2.5");
}

</style>
