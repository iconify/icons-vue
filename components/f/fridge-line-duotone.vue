<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bub6scbyt"/><path class="pgfv6z-_o"/><path class="xc_fo9bdv"/><path class="f26ggybga"/><path class="tadkrybvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fridge-line-duotone" /></template>
<style>
.bub6scbyt {
  d: path("M12 21C8.22876 21 6.34315 21 5.17157 19.8284C4 18.6569 4 16.7712 4 13V10C4 6.22876 4 4.34315 5.17157 3.17157C6.34315 2 8.22876 2 12 2C15.7712 2 17.6569 2 18.8284 3.17157C20 4.34315 20 6.22876 20 10V13C20 16.7712 20 18.6569 18.8284 19.8284C17.6569 21 15.7712 21 12 21Z");
}

.f26ggybga {
  d: path("M17 14L17 16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pgfv6z-_o {
  stroke-linejoin: round;
  d: path("M17 21V22H16V21M8 21V22H7V21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tadkrybvn {
  d: path("M20 11.5H4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xc_fo9bdv {
  d: path("M17 7L17 9");
}

</style>
