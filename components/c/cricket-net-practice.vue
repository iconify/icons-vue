<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l42630oed"/><path class="xe8slm__f"/><path class="i840415qb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cricket-net-practice" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i840415qb {
  fill: currentColor;
  d: path("M14.75 19.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.l42630oed {
  d: path("M3 21V4h18v17");
}

.xe8slm__f {
  d: path("m3 9l4.5-5L12 9l4.5-5L21 9zm10.975 4.025za1.75 1.75 0 0 1 0 2.475L11.5 17.975a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475l2.475-2.475a1.75 1.75 0 0 1 2.475 0M9 18l-3 3");
}

</style>
