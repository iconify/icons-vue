<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vkj93pbwb"/><circle class="hvgdv64iz"/><path class="z32e36b5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ai-cost-meter-sharp" /></template>
<style>
.hvgdv64iz {
  cx: 12px;
  cy: 13px;
  r: 1.75px;
}

.vkj93pbwb {
  d: path("M3.75 13a8.25 8.25 0 0 1 16.5 0m-7.18-1.38L15.5 8.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z32e36b5m {
  d: path("M5.75 17.25h12.5v4H5.75z");
}

</style>
