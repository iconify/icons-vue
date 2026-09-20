<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ugh6y_a-z"/><path class="hvurf-2wj"/><path class="y5d_59vhw"/><path class="q12h31yct"/><path class="mcubrkb2y"/><path class="k7u-15-va"/><path class="ghf6zpb7j"/><path class="c4khiwgvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:account-number-duotone-bold" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.ghf6zpb7j {
  d: path("M14 12v6");
}

.hvurf-2wj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k7u-15-va {
  d: path("M10 12v6");
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

.q12h31yct {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ugh6y_a-z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y5d_59vhw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
