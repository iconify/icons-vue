<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yw0x1wbxg"/><path class="fkj0dbb6f"/><path class="mcrp9i-9c"/><path class="x8_s66bwx"/><path class="mcubrkb2y"/><path class="k7u-15-va"/><path class="ghf6zpb7j"/><path class="c4khiwgvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:account-number-duotone-thin" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.fkj0dbb6f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ghf6zpb7j {
  d: path("M14 12v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7u-15-va {
  d: path("M10 12v6");
}

.mcrp9i-9c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

.x8_s66bwx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yw0x1wbxg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
