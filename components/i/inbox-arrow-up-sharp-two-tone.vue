<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dxwlyvbtz"/><path class="d4z6f_4nh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox-arrow-up-sharp-two-tone" /></template>
<style>
.d4z6f_4nh {
  d: path("M18.6996 6.7715L22 12.1534L22 20L2 20L2 12.1534L5.3004 6.7715M2 13L8 13L10 16L14 16L16 13L22 13M12 12L12 4M8.7071 7.2929L12 4L15.2929 7.2929");
}

.dxwlyvbtz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 13L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 13L8 13L10 16L14 16L16 13Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
