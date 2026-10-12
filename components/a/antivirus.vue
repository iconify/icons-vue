<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="pfpt48slt"/><path class="ojns-rv_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:antivirus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ojns-rv_m {
  d: path("M12 6.5V3.75m0 13.75v2.75M6.5 12H3.75m13.75 0h2.75M8.11 8.11L6.17 6.17m9.72 9.72l1.94 1.94m-1.94-9.72l1.94-1.94m-9.72 9.72l-1.94 1.94M10 10l4 4m0-4l-4 4");
}

.pfpt48slt {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
}

</style>
