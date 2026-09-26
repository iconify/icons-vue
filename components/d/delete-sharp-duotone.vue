<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l2x696bfp"/><path class="zr1yegbzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:delete-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l2x696bfp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1.2475 11.3415L8.2474 3.3415C8.4373 3.1245 8.7116 3 9 3L22 3C22.5523 3 23 3.4477 23 4L23 20C23 20.5523 22.5523 21 22 21L9 21C8.7116 21 8.4373 20.8755 8.2474 20.6585L1.2475 12.6585C1.088 12.4762 1 12.2422 1 12C1 11.7578 1.088 11.5238 1.2475 11.3415Z");
  stroke: none;
}

.zr1yegbzr {
  d: path("M10.7071 8.7071L17.2929 15.2929M17.2929 8.7071L10.7071 15.2929");
}

</style>
