<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r4tzxzl2o"/><path class="ig10efbdv"/><path class="mwg8pgbcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hose-timer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ig10efbdv {
  d: path("M6 12.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.mwg8pgbcw {
  d: path("M11 10.5v2h1.75m-1.75 5v1a2.5 2.5 0 0 0 2.5 2.5h8");
}

.r4tzxzl2o {
  d: path("M2.5 4.5H11v3M6 2v2.5");
}

</style>
