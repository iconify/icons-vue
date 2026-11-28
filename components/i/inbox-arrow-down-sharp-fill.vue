<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="cxp5xrx_h"/><path class="uz79asbow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox-arrow-down-sharp-fill" /></template>
<style>
.cxp5xrx_h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 13H8L10 16H14L16 13H22V19C22 19.5523 21.552 20 21 20H3C2.448 20 2 19.5523 2 19V13Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uz79asbow {
  d: path("M18.603 6.6133L22 12.1534V13M22 13V20H2V13M22 13H16L14 16H10L8 13H2M2 13V12.1534L5.398 6.6133M12 3V11M15.293 7.7071L12 11L8.707 7.7071");
}

</style>
