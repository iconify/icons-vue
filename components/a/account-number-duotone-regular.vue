<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k5ecbgu2w"/><path class="yc4-zordy"/><path class="g-mrv1hbe"/><path class="eljxzwbgp"/><path class="mcubrkb2y"/><path class="k7u-15-va"/><path class="ghf6zpb7j"/><path class="c4khiwgvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:account-number-duotone-regular" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.eljxzwbgp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g-mrv1hbe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ghf6zpb7j {
  d: path("M14 12v6");
}

.k5ecbgu2w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k7u-15-va {
  d: path("M10 12v6");
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yc4-zordy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
