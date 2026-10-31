<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j8vnkcbef"/><path class="q75b-pboy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bath-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j8vnkcbef {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11C2 10.4477 2.4477 10 3 10L21 10C21.5523 10 22 10.4477 22 11L22 19C22 19.5523 21.5523 20 21 20L3 20C2.4477 20 2 19.5523 2 19L2 11Z");
  stroke: none;
}

.q75b-pboy {
  d: path("M3 11L3 19L21 19L21 11M1 11L23 11M8 19L6.7236 21.5528M16 19L17.2764 21.5528M3 11L3 6C3 4.3431 4.3431 3 6 3C7.0463 3 8.0169 3.5451 8.5615 4.4384M7.2071 5.7929L10.2929 2.7071");
}

</style>
