<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="soke5acqb"/><circle class="yukx6eb0d"/><path class="sw8n7ywyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:location-plus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.soke5acqb {
  d: path("M12 21.25c-.35 0-.7-.13-.95-.38C8.1 18.1 4.75 14.4 4.75 10a7.25 7.25 0 0 1 14.5 0c0 .85-.12 1.67-.35 2.5");
}

.sw8n7ywyp {
  d: path("M17.5 14.75v5.5m-2.75-2.75h5.5");
}

.yukx6eb0d {
  cx: 12px;
  cy: 10px;
  r: 2.5px;
}

</style>
