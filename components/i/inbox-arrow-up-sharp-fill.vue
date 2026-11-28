<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="cxp5xrx_h"/><path class="hh0v3obvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox-arrow-up-sharp-fill" /></template>
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

.hh0v3obvk {
  d: path("M18.7 6.7715L22 12.1534V13M22 13V20H2V13M22 13H16L14 16H10L8 13H2M2 13V12.1534L5.3 6.7715M12 12V4M15.293 7.2929L12 4L8.707 7.2929");
}

</style>
