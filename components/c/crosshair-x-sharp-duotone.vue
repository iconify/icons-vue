<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bcje72bbx"/><path class="ogpji3bqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crosshair-x-sharp-duotone" /></template>
<style>
.bcje72bbx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12C21 16.9706 16.9706 21 12 21C7.0294 21 3 16.9706 3 12C3 7.0294 7.0294 3 12 3C16.9706 3 21 7.0294 21 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ogpji3bqc {
  d: path("M12 1L12 7M12 23L12 17M1 12L7 12M23 12L17 12M9.2071 9.2071L14.7929 14.7929M14.7929 9.2071L9.2071 14.7929");
}

</style>
