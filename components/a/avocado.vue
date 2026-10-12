<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yjbw8rhwu"/><circle class="gcog520pu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:avocado" /></template>
<style>
.gcog520pu {
  cx: 12px;
  cy: 14.25px;
  r: 3.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjbw8rhwu {
  d: path("M12 2.75c-2.6 0-3.75 2.6-4.5 5.25c-.55 1.9-2.75 3.5-2.75 6a7.25 7.25 0 0 0 14.5 0c0-2.5-2.2-4.1-2.75-6c-.75-2.65-1.9-5.25-4.5-5.25");
}

</style>
