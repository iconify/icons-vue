<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kc_g0cb8o"/><path class="uw0-00x8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-stored-data-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kc_g0cb8o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 20L9 20C4.5817 20 1 16.4183 1 12C1 7.5817 4.5817 4 9 4L21 4C22.1046 4 23 4.8954 23 6C23 6.6297 22.7035 7.2223 22.2001 7.5999C20.8151 8.6387 20 10.2689 20 12C20 13.7311 20.8151 15.3613 22.2 16.4C22.7035 16.7777 23 17.3703 23 18C23 19.1046 22.1046 20 21 20Z");
  stroke: none;
}

.uw0-00x8k {
  d: path("M22 6C22 6.3148 21.8518 6.6111 21.6 6.8C19.9633 8.0276 19 9.9541 19 12C19 14.0459 19.9633 15.9724 21.6 17.2C21.8518 17.3889 22 17.6852 22 18C22 18.5523 21.5523 19 21 19L9 19C5.134 19 2 15.866 2 12C2 8.134 5.134 5 9 5L21 5C21.5523 5 22 5.4477 22 6Z");
}

</style>
