<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lnfkolbcu"/><path class="po21esbuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:concierge-bell-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lnfkolbcu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.055 14C3.3425 11.4224 4.7285 9.0943 6.8574 7.6131C8.365 6.5621 10.1585 5.9986 11.9963 5.9986C12.3745 5.9986 12.7524 6.0224 13.1277 6.0701C15.6564 6.3889 17.9312 7.7653 19.3869 9.8574C20.2447 11.0862 20.7804 12.5105 20.945 14L22 14C22.5523 14 23 14.4477 23 15L23 21C23 21.5523 22.5523 22 22 22L2 22C1.4477 22 1 21.5523 1 21L1 15C1 14.4477 1.4477 14 2 14L3.055 14Z");
  stroke: none;
}

.po21esbuf {
  d: path("M2 15L22 15L22 21L2 21ZM4 15C4 10.5817 7.5817 7 12 7C16.4183 7 20 10.5817 20 15M12 7L12 3M8 3L16 3");
}

</style>
