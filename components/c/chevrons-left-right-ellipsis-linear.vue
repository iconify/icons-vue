<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="th_2vrbuv"/><path class="oorbizavx"/><path class="ghv12qbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-left-right-ellipsis-linear" /></template>
<style>
.ghv12qbis {
  d: path("M8 12H8.009M11.991 12H12M15.991 12H16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oorbizavx {
  d: path("M8 6L2 12L8 18");
}

.th_2vrbuv {
  d: path("M16 6L22 12L16 18");
}

</style>
