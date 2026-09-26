<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ouh-gobdj"/><path class="xilno108m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-6-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ouh-gobdj {
  stroke-opacity: 0.4;
  d: path("M2 3L2 21M11 3L11 21M2 12L11 12");
}

.xilno108m {
  d: path("M17 18C17 16.8954 17.8954 16 19 16C20.1046 16 21 16.8954 21 18C21 19.1046 20.1046 20 19 20C17.8954 20 17 19.1046 17 18ZM17 18C17 15.5811 18.7178 13.4633 21 13L21.8011 12.8374");
}

</style>
