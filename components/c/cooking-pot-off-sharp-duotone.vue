<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="f8y2knsqk"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cooking-pot-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.f8y2knsqk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21 21C21 21.5523 20.5523 22 20 22L4 22C3.4477 22 3 21.5523 3 21L3 12.0001L1 12.0001L1 10.0001L3.988 10.0001C3.9913 10 3.9947 10 3.998 10C3.9987 10 3.9993 10 4 10L10 10L21 21ZM8.0001 8.0001L3 8.0001L3 6.0001L6.0001 6.0001L8.0001 8.0001ZM13.6569 10L20 10C20.0007 10 20.0013 10 20.002 10C20.0053 10 20.0087 10 20.012 10.0001L23 10.0001L23 12.0001L21 12.0001L21 17.3431L13.6569 10ZM7 3.3431L7 3C7 2.4477 7.4477 2 8 2L16 2C16.5523 2 17 2.4477 17 3L17 6.0001L21 6.0001L21 8.0001L11.657 8.0001L7 3.3431Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
