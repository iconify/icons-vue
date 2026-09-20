<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="c58ve3zov"/><path class="w5kgvzb8e"/><path class="n3cxssblb"/><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="u1mon9cdo"/><path class="o_qgmvj5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:change-capture-duotone-thin" /></template>
<style>
.c58ve3zov {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 10h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ck7sgubpk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.n3cxssblb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 13 -3 3h2.5l-3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o_qgmvj5j {
  d: path("m20 13 -3 3h2.5l-3 3");
}

.u1mon9cdo {
  d: path("M3 15h9");
}

.w5kgvzb8e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 15h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>
