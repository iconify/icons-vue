<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e1e4asb_u"/><path class="v05i0mbel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bound-report" /></template>
<style>
.e1e4asb_u {
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v12a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V6A3.5 3.5 0 0 1 8 2.5m-.25 0v19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v05i0mbel {
  d: path("M12.25 6H15a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 15 10h-2.75a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 12.25 6");
}

</style>
