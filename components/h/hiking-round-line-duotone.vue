<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="lgksoiblo"/><path class="rut37sbqn"/><path class="blj8bd-xv"/><path class="cu7xy9b9y"/><path class="lu37x4boy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hiking-round-line-duotone" /></template>
<style>
.blj8bd-xv {
  stroke-linejoin: round;
  d: path("M19.0009 10.5L18.5776 10.8528C17.0124 12.1571 14.8234 12.4112 13.0009 11.5C11.8385 10.8025 10.3457 11.5521 10.2108 12.901L10.1422 13.5871C10.0557 14.4523 10.4677 15.2917 11.2051 15.7526L11.5383 15.9609C13.0894 16.9303 14.0962 18.5707 14.2583 20.3926L14.4013 22");
}

.cu7xy9b9y {
  d: path("M19 22V8");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgksoiblo {
  cx: 11.5px;
  cy: 4.5px;
  r: 2.5px;
}

.lu37x4boy {
  d: path("M9 10L6.6114 10.1437C5.87495 10.1881 5.24941 10.6999 5.05846 11.4143C4.89043 12.043 5.09113 12.713 5.57688 13.1448L7.66367 15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rut37sbqn {
  d: path("M9 17.5C9 17.5 8.57441 19.1192 8 20C7.39661 20.9252 6 22 6 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
