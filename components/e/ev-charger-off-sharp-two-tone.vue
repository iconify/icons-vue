<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="a-ljtccnt"/><path class="kn-22k09p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-off-sharp-two-tone" /></template>
<style>
.a-ljtccnt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M1.7071 1.7071L15 15L15 22C15 22.5523 14.5523 23 14 23L2 23C1.4477 23 1 22.5523 1 22L1 2.4142L1.7071 1.7071ZM19 5L21 5L21 3L23 3L23 10C23 10.5523 22.5523 11 22 11L21 11L21 15.3431L19 15.3431L19 11L18 11C17.4477 11 17 10.5523 17 10L17 3L19 3L19 5ZM4.7426 1L14 1C14.5523 1 15 1.4477 15 2L15 11.2574L4.7426 1Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kn-22k09p {
  d: path("M14 14L14 22L2 22L2 2M14 22L22 22M14 17L17 17M8.5714 8.5714L6 12L10 12L6.7 16.4M1.7071 1.7071L22.2929 22.2929");
}

</style>
