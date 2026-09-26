<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n7g6ddb3h"/><path class="mejzxfv0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-zap-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mejzxfv0x {
  d: path("M20.2929 1.7071L17 5L21 5L17.7071 8.2929");
}

.n7g6ddb3h {
  fill: currentColor;
  d: path("M22 11L21.9998 22.0002C21.9998 22.5525 21.5521 23.0002 20.9998 23.0002L16 23.0002L16 14.0002L8 14.0002L8 23.0002L3.0002 23.0002C2.4479 23.0002 2.0002 22.5525 2.0002 22.0002L2 10.9999C2 10.706 2.1293 10.4269 2.3536 10.2369L11.3881 3.2069C11.7482 2.9266 12.2524 2.9258 12.6135 3.2048L14 4.2856L14 11L22 11Z");
  stroke: none;
}

</style>
