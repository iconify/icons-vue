<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j8gekbbtm"/><path class="f8wc7jbfd"/><path class="p52tuibwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:armchair-sharp-duotone" /></template>
<style>
.f8wc7jbfd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 21L19 21L22 21C22.5523 21 23 20.5523 23 20L23 13C23 11.3431 21.6569 10 20 10C18.3431 10 17 11.3431 17 13L7 13C7 11.3431 5.6569 10 4 10C2.3431 10 1 11.3431 1 13L1 20C1 20.5523 1.4477 21 2 21L5 21Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j8gekbbtm {
  fill: currentColor;
  d: path("M3 10.1707L3 2C3 1.4477 3.4477 1 4 1L12 1L20 1C20.5523 1 21 1.4477 21 2L21 10.1707C20.6872 10.0601 20.3506 10 20 10C18.3431 10 17 11.3431 17 13L7 13C7 11.3431 5.6569 10 4 10C3.6494 10 3.3128 10.0601 3 10.1707Z");
  stroke: none;
}

.p52tuibwo {
  d: path("M19 20L19 22L19 23M5 20L5 22L5 23");
}

</style>
