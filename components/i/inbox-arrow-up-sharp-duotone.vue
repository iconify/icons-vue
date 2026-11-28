<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="khp8tkftq"/><path class="e2w5ib8gd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox-arrow-up-sharp-duotone" /></template>
<style>
.e2w5ib8gd {
  d: path("M1 13L8 13L10 16L14 16L16 13L23 13M12 12L12 4M8.7071 7.2929L12 4L15.2929 7.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.khp8tkftq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 13L21 12.4356L17.8471 7.2943L19.5521 6.2487L22.8525 11.6306C22.9489 11.7879 23 11.9689 23 12.1534L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 12.1534C1 11.9689 1.0511 11.7879 1.1475 11.6306L4.4479 6.2487L6.1529 7.2943L3 12.4356L3 13L8 13L10 16L14 16L16 13Z");
  stroke: none;
}

</style>
