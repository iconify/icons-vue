<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwi87ac4g"/><path class="bm7onkbce"/><path class="rweggx0cr"/><path class="e77gki8ci"/><path class="n92b0ebji"/><path class="m7aa3ibix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hold-at-depot-duotone-thin" /></template>
<style>
.bm7onkbce {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e77gki8ci {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m7aa3ibix {
  d: path("M14.5 11v6");
}

.n92b0ebji {
  d: path("M9.5 11v6");
}

.nwi87ac4g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20V10l3 -3h14l3 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rweggx0cr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
