<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lg9uabb_p"/><path class="sl8osqjdc"/><path class="l58vj2q7k"/><path class="tkeq0bpvv"/><path class="yw-dgs_nk"/><path class="ivdpkbnwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guardrail-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivdpkbnwt {
  d: path("m11 9 3 3 -3 3");
}

.l58vj2q7k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lg9uabb_p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sl8osqjdc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tkeq0bpvv {
  d: path("M18 4v16");
}

.yw-dgs_nk {
  d: path("M4 12h10");
}

</style>
