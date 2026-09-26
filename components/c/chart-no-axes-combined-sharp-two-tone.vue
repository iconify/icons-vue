<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i65lcpftl"/><path class="tziaf_0sp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-no-axes-combined-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i65lcpftl {
  stroke-opacity: 0.4;
  d: path("M4 22L4 16M8 22L8 11M12 22L12 14M16 22L16 12.5M20 22L20 9");
}

.tziaf_0sp {
  d: path("M22.2781 2.7682L13 10.5L7.5 6.5L1.7071 12.2929");
}

</style>
