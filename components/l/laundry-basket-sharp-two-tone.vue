<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oqvhjkbig"/><path class="srgitlbil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laundry-basket-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqvhjkbig {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.6568 10L21.9976 10C22.5499 10 22.9976 10.4477 22.9976 11C22.9976 11.0658 22.9911 11.1314 22.9782 11.1959L20.9806 21.1959C20.8872 21.6634 20.4768 22 20 22L4 22C3.5232 22 3.1128 21.6634 3.0194 21.1959L1.0218 11.1959C1.0089 11.1314 1.0024 11.0658 1.0024 11C1.0024 10.4477 1.4501 10 2.0024 10L3.3432 10C3.1175 9.3618 3 8.6858 3 8C3 4.6863 5.6863 2 9 2C10.0574 2 11.0915 2.2793 12 2.8038C12.9085 2.2793 13.9426 2 15 2C18.3137 2 21 4.6863 21 8C21 8.6858 20.8825 9.3618 20.6568 10Z");
  stroke: none;
}

.srgitlbil {
  d: path("M5 11C4.3509 10.1345 4 9.0819 4 8C4 5.2386 6.2386 3 9 3C10.0819 3 11.1345 3.3509 12 4C12.8655 3.3509 13.9181 3 15 3C17.7614 3 20 5.2386 20 8C20 9.0819 19.6491 10.1345 19 11M8 14L8 15L8 17L8 18M12 14L12 15L12 17L12 18M16 14L16 15L16 17L16 18M2.0024 11L21.9976 11L20 21L4 21Z");
}

</style>
