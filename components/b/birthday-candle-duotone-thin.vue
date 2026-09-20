<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="twp5c8mgm"/><path class="iv55jvbip"/><path class="facaoccxd"/><path class="c4khiwgvb"/><path class="wv_9g9b3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:birthday-candle-duotone-thin" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.facaoccxd {
  d: path("M8 21V11h8v10Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iv55jvbip {
  fill: currentColor;
  d: path("M12 9c-2.5 -2 -2.5 -5 0 -7 2.5 2 2.5 5 0 7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.twp5c8mgm {
  fill: currentColor;
  d: path("M8 21V11h8v10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wv_9g9b3l {
  d: path("M12 9c-2.5 -2 -2.5 -5 0 -7 2.5 2 2.5 5 0 7");
}

</style>
