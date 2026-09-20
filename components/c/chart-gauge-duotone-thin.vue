<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zu-ymbcar"/><path class="d2j4ppeho"/><path class="b4508csym"/><path class="msvyyebim"/><path class="ng35sb6yg"/><path class="u4c9tcc0l"/><path class="t50oj1u1o"/><path class="eyettubom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-gauge-duotone-thin" /></template>
<style>
.b4508csym {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d2j4ppeho {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eyettubom {
  d: path("M18.5 16H21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.msvyyebim {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 16H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.t50oj1u1o {
  d: path("M3 16h2.5");
}

.u4c9tcc0l {
  d: path("m12 16 5 -5");
}

.zu-ymbcar {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
