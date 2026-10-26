<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="evcvpwbli"/><path class="dvfqmf-7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-front-off-sharp-two-tone" /></template>
<style>
.dvfqmf-7l {
  d: path("M20 20L17.5 20L17 18L7 18L6.5 20L3 20L3 10L10 10M5.0513 10L5.3518 9L6.4482 6.4482M5.3518 9L2.5 9M8 12.5L8 15.5M1.7071 1.7071L22.2929 22.2929");
}

.evcvpwbli {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21.5 9.1338C21.8095 9.3124 22.0002 9.6427 22 10.0001L22 16.3432L22 18.3431L6.8757 3.2188C7.0529 3.0771 7.2731 3 7.5 3L16.5 3C16.8997 3 17.2611 3.238 17.4188 3.6053L19.3069 8L21.5 8L21.5 9.1338ZM18.1715 21L17.5 21C17.0411 21 16.6411 20.6877 16.5299 20.2425L16.2351 19.0636L16.1715 19L7.7808 19L7.4701 20.2425C7.3589 20.6877 6.9589 21 6.5 21L3 21C2.4477 21 2 20.5523 2 20L2 10C2 9.4477 2.4477 9 3 9L4.3076 9L4.3941 8.7122C4.405 8.6758 4.418 8.6401 4.433 8.6052L5.6868 5.6868L21 21.0001L18.1715 21Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
