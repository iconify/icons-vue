<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x5beyjd8g"/><path class="inp0fub_p"/><path class="b5x3oqb_u"/><path class="jlpxneb5g"/><path class="v0y09obth"/><path class="zy54a7bml"/><path class="m27ljac1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:export-report-duotone-thin" /></template>
<style>
.b5x3oqb_u {
  d: path("M6 10v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.inp0fub_p {
  d: path("M2 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.jlpxneb5g {
  d: path("M9 8v8");
}

.m27ljac1c {
  d: path("m18 9 3 3 -3 3");
}

.v0y09obth {
  d: path("M12 12v4");
}

.x5beyjd8g {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zy54a7bml {
  d: path("M17 12h4");
}

</style>
