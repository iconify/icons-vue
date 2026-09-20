<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vpuel0dtu"/><path class="nv604obcx"/><path class="q01xb8b0t"/><path class="ngykh7bvw"/><path class="crv4i00bu"/><path class="nfb4ipisv"/><path class="b603-acaz"/><path class="pqv-otbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:llm-trace-duotone-thin" /></template>
<style>
.b603-acaz {
  d: path("M10 12h8");
}

.crv4i00bu {
  d: path("M4 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nfb4ipisv {
  d: path("M7 7h7");
}

.ngykh7bvw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nv604obcx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 7h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pqv-otbrp {
  d: path("M13 17h8");
}

.q01xb8b0t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vpuel0dtu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
