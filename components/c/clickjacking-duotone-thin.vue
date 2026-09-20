<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c13n5ccfl"/><path class="jzww46baz"/><path class="n09nomjwg"/><path class="zzniibc1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:clickjacking-duotone-thin" /></template>
<style>
.c13n5ccfl {
  fill: currentColor;
  d: path("M15 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzww46baz {
  fill: currentColor;
  d: path("M9 8v7l2 -2h3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n09nomjwg {
  d: path("M15 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
}

.zzniibc1m {
  d: path("M9 8v7l2 -2h3Z");
}

</style>
