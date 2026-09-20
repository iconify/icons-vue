<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wxaqw6igd"/><path class="oaf82wpzn"/><path class="yw0x1wbxg"/><path class="bv1yo3yzc"/><path class="mcubrkb2y"/><path class="v9tp15bnh"/><path class="o3jwr8bmt"/><path class="fa5_klbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:interest-earned-duotone-thin" /></template>
<style>
.bv1yo3yzc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 18 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fa5_klbta {
  d: path("M13.5 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

.o3jwr8bmt {
  d: path("m9 18 6 -6");
}

.oaf82wpzn {
  fill: currentColor;
  d: path("M13.5 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v9tp15bnh {
  d: path("M8.5 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.wxaqw6igd {
  fill: currentColor;
  d: path("M8.5 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yw0x1wbxg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
