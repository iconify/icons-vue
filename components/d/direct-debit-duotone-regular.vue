<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k5ecbgu2w"/><path class="eljxzwbgp"/><path class="w2lyggbtq"/><path class="mcubrkb2y"/><path class="c4khiwgvb"/><path class="iq7hdacem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:direct-debit-duotone-regular" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.eljxzwbgp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iq7hdacem {
  d: path("M10.5 12.5 8 15l2.5 2.5");
}

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

.w2lyggbtq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 12.5 8 15l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
