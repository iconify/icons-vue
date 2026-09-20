<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="c58ve3zov"/><path class="m_hvadc8j"/><path class="syng65bge"/><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="ephqv81ta"/><path class="zrtfv65fm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:infinite-scroll-duotone-thin" /></template>
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

.ephqv81ta {
  d: path("m9.5 14 2.5 2.5 2.5 -2.5");
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

.m_hvadc8j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 14 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.syng65bge {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 18.5 12 21l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x50q_4bdr {
  d: path("M3 10h18");
}

.zrtfv65fm {
  d: path("M9.5 18.5 12 21l2.5 -2.5");
}

</style>
