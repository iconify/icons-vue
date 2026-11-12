<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zowiwwbmr"/><path class="zyly0dhik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-down-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zowiwwbmr {
  d: path("M6 6L18 18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zyly0dhik {
  d: path("M18 9L18 18L9 18");
}

</style>
