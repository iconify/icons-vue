<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="npetygxsp"/><path class="q48rwotap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:church-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.npetygxsp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 1V3H15V5H13V7.11L18.59 11.19C18.847 11.38 19 11.68 19 12V13.38L22.447 15.11C22.786 15.27 23 15.62 23 16V22C23 22.55 22.552 23 22 23H2C1.448 23 1 22.55 1 22V16C1 15.62 1.214 15.27 1.553 15.11L5 13.38V12C5 11.68 5.153 11.38 5.41 11.19L11 7.11V5H9V3H11V1H13Z");
  stroke: none;
}

.q48rwotap {
  d: path("M6 22V14M6 22H2V16L6 14M6 22H10M6 14V12L12 7.61M10 22V18C10 16.9 10.895 16 12 16C13.105 16 14 16.9 14 18V22M10 22H14M12 7.61L18 12V14M12 7.61V4M14 22H18M18 14V22M18 14L22 16V22H18M12 4V1M12 4H9M12 4H15");
}

</style>
