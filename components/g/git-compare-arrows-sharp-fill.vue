<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h-b2bgbtf"/><path class="hz7_q3dyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-compare-arrows-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h-b2bgbtf {
  d: path("M6 8L6 18L10.8535 18M13.1465 6L18 6L18 16M15.0858 3.7071L12.7929 6L15.0858 8.2929M8.9142 15.7071L11.2071 18L8.9142 20.2929");
}

.hz7_q3dyh {
  fill: currentColor;
  d: path("M6 2C8.0711 2 10 3.9289 10 6C10 8.0711 8.0711 10 6 10C3.9289 10 2 8.0711 2 6C2 3.9289 3.9289 2 6 2ZM18 14C15.9289 14 14 15.9289 14 18C14 20.0711 15.9289 22 18 22C20.0711 22 22 20.0711 22 18C22 15.9289 20.0711 14 18 14Z");
  stroke: none;
}

</style>
