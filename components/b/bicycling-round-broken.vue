<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="mrtq9bbsf"/><circle class="dos_yhbgg"/><circle class="ez1x61b2a"/><path class="ogczms5ye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bicycling-round-broken" /></template>
<style>
.dos_yhbgg {
  cx: 6px;
  cy: 18px;
  r: 3px;
}

.ez1x61b2a {
  cx: 18px;
  cy: 18px;
  r: 3px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mrtq9bbsf {
  cx: 14px;
  cy: 4px;
  r: 2px;
}

.ogczms5ye {
  d: path("M18.5006 10H14.5829C14.2059 10 13.84 9.87216 13.5451 9.63736L11.3867 7.91919C10.1201 6.91087 8.25241 7.27105 7.45157 8.67809C6.67635 10.0401 7.25265 11.7736 8.68902 12.4004M12.0006 18L12.761 16.2258C13.1703 15.2709 12.732 14.1646 11.7797 13.749");
}

</style>
