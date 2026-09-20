<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bo51iypxr"/><path class="t27ig7bvg"/><path class="s_rpgcb_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:double-tap-outline-thin" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s_rpgcb_d {
  d: path("M19.07 4.93a10 10 0 1 1 -14.14 0");
}

.t27ig7bvg {
  d: path("M16.24 7.76a6 6 0 1 1 -8.5 0");
}

</style>
