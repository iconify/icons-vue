<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i1fxq_b7e"/><path class="aufz4obiv"/><path class="qd8mnybib"/><path class="v5td4_4qf"/><path class="km504hb-m"/><path class="w7wsu271f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:circuit-break-duotone-thin" /></template>
<style>
.aufz4obiv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 16H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1fxq_b7e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h6.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.km504hb-m {
  d: path("M15.5 16H22");
}

.qd8mnybib {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8.5 16 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v5td4_4qf {
  d: path("M2 16h6.5");
}

.w7wsu271f {
  d: path("m8.5 16 8 -8");
}

</style>
