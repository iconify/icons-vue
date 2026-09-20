<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k5ecbgu2w"/><path class="rsnlxle2w"/><path class="zc84ylb-p"/><path class="mcubrkb2y"/><path class="ohhz_s35v"/><path class="qox9oe20g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cash-withdraw-duotone-regular" /></template>
<style>
.k5ecbgu2w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.ohhz_s35v {
  d: path("M12 12v6");
}

.qox9oe20g {
  d: path("M9.5 14.5 12 12l2.5 2.5");
}

.rsnlxle2w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zc84ylb-p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 14.5 12 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
