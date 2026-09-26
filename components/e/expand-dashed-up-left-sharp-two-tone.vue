<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s_e2iibux"/><path class="ani1-ubxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-left-sharp-two-tone" /></template>
<style>
.ani1-ubxv {
  stroke-opacity: 0.4;
  d: path("M3 12L3 8.6667M3 6.6667L3 3L6.6667 3M8.6667 3L12 3");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s_e2iibux {
  d: path("M18 14L18 3M21.2929 6.2929L18 3L14.7071 6.2929M14 18L3 18M6.2929 14.7071L3 18L6.2929 21.2929");
}

</style>
