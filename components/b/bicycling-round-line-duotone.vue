<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="mrtq9bbsf"/><circle class="vu97hgmrr"/><circle class="ym7z_obxz"/><path class="l1rf140op"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bicycling-round-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l1rf140op {
  d: path("M18.5006 10H14.5829C14.2059 10 13.84 9.87216 13.5451 9.63736L11.3867 7.91919C10.1201 6.91087 8.25241 7.27105 7.45157 8.67809C6.67635 10.0401 7.25265 11.7736 8.68902 12.4004L11.7797 13.749C12.732 14.1646 13.1703 15.2709 12.761 16.2258L12.0006 18");
}

.mrtq9bbsf {
  cx: 14px;
  cy: 4px;
  r: 2px;
}

.vu97hgmrr {
  cx: 6px;
  cy: 18px;
  r: 3px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ym7z_obxz {
  cx: 18px;
  cy: 18px;
  r: 3px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
