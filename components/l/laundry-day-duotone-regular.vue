<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w18s0ubfz"/><path class="w2xyblbcw"/><path class="sr2k46y1n"/><path class="kamdbib6v"/><path class="pqojzri_o"/><path class="sno-u_b6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:laundry-day-duotone-regular" /></template>
<style>
.kamdbib6v {
  d: path("M2 7h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqojzri_o {
  d: path("M6 7v7h4V7");
}

.sno-u_b6h {
  d: path("M14 7v10h4V7");
}

.sr2k46y1n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 7v10h4V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w18s0ubfz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w2xyblbcw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 7v7h4V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
