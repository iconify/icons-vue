<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ra6o68b-z"/><path class="sooj-ebve"/><path class="j2r1pso3k"/><path class="u94nv5b1o"/><path class="md3qg6xkk"/><path class="bvirm9d4j"/><path class="sxlwlmkmh"/><path class="n90p24bmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:api-bridge-duotone-thin" /></template>
<style>
.bvirm9d4j {
  d: path("M20 6v12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2r1pso3k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.md3qg6xkk {
  d: path("M4 6v12");
}

.n90p24bmq {
  d: path("m10 10 2 2 -2 2");
}

.ra6o68b-z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sooj-ebve {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

.u94nv5b1o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
