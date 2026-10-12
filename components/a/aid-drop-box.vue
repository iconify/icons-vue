<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-e5pbu_e"/><rect class="gwsam3bap"/><path class="ffo-swptt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aid-drop-box" /></template>
<style>
.ffo-swptt {
  d: path("M12 15.75v3.5m-1.75-1.75h3.5");
}

.gwsam3bap {
  width: 9px;
  height: 8px;
  x: 7.5px;
  y: 13.25px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-e5pbu_e {
  d: path("M3.75 9.25a8.25 6.25 0 0 1 16.5 0Zm.75 0l3.75 4m11.25-4l-3.75 4");
}

</style>
