<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dktry7bqc"/><path class="q9_ywob1q"/><path class="jzwai4b0o"/><path class="bo51iypxr"/><path class="t27ig7bvg"/><path class="s_rpgcb_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:double-tap-duotone-thin" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.jzwai4b0o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.07 4.93a10 10 0 1 1 -14.14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q9_ywob1q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.24 7.76a6 6 0 1 1 -8.5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s_rpgcb_d {
  d: path("M19.07 4.93a10 10 0 1 1 -14.14 0");
}

.t27ig7bvg {
  d: path("M16.24 7.76a6 6 0 1 1 -8.5 0");
}

</style>
