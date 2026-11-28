<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="mpp__xbid"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-off-sharp-fill" /></template>
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

.mpp__xbid {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 21L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 4C3 3.7239 3.1119 3.4739 3.2929 3.2929ZM6 2.3431L6 2C6 1.4477 6.4477 1 7 1L17 1C17.5523 1 18 1.4477 18 2L18 3L20 3C20.5523 3 21 3.4477 21 4L21 17.3431L9.6569 6L16 6L16 3L8 3L8 4.3431Z");
  stroke: none;
}

</style>
