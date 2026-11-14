<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kraz7acna"/><path class="tod8vrbwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:desktop-app-dev" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kraz7acna {
  d: path("M6.875 3h10.25A4.375 4.375 0 0 1 21.5 7.375v4.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 12.125v-4.75A4.375 4.375 0 0 1 6.875 3M12 16.5v4m-4 0h8");
}

.tod8vrbwb {
  d: path("M7.75 6h8.5A1.75 1.75 0 0 1 18 7.75v4a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 6 11.75v-4A1.75 1.75 0 0 1 7.75 6M6 8.75h12");
}

</style>
