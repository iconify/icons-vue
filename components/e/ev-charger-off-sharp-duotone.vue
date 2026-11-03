<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="ui_tlsbku"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ui_tlsbku {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M15 18L15 21L21 21L22.2929 22.2929L21.5858 23L2 23C1.4477 23 1 22.5523 1 22L1 2.4142L1.7071 1.7071L7.8571 7.8571L5.2 11.4C5.0701 11.5731 4.9998 11.7837 4.9998 12.0002C4.9998 12.5525 5.4477 13.0002 6 13L8 13L5.9 15.8L7.5 17L10.8 12.6C10.9299 12.4269 11.0002 12.2163 11.0002 11.9998C11.0002 11.4475 10.5523 10.9998 10 11L8 11L9.2857 9.2857L15 15L15 16L17 16L17 18L15 18ZM19 5L21 5L21 3L23 3L23 10C23 10.5523 22.5523 11 22 11L21 11L21 15.3431L19 15.3431L19 11L18 11C17.4477 11 17 10.5523 17 10L17 3L19 3L19 5ZM4.6569 1L14 1C14.5523 1 15 1.4477 15 2L15 11.3431L4.6569 1Z");
  stroke: none;
}

</style>
