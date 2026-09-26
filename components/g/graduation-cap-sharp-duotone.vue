<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k9_6zp9ba"/><path clip-rule="evenodd" class="i2p_dkbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:graduation-cap-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i2p_dkbsa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.3714 4.0715L22.3714 8.0715C22.751 8.2234 23 8.5911 23 9C23 9.4089 22.751 9.7766 22.3714 9.9285L12.3714 13.9285C12.2533 13.9757 12.1272 14 12 14C11.8728 14 11.7467 13.9757 11.6286 13.9285L1.6286 9.9285C1.249 9.7766 1 9.4089 1 9C1 8.5911 1.249 8.2234 1.6286 8.0715L11.6286 4.0715C11.7467 4.0243 11.8728 4 12 4C12.1272 4 12.2533 4.0243 12.3714 4.0715Z");
  stroke: none;
}

.k9_6zp9ba {
  stroke-opacity: 0.4;
  d: path("M6 10.6L6 16.7901C7.6737 18.2165 9.8009 19 12 19C14.1991 19 16.3263 18.2165 18 16.7901L18 10.6M2 9L2 16");
}

</style>
