<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zmp2owtdl"/><path class="rnfdpvb6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:batch-release" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnfdpvb6d {
  d: path("M8.5 14.5L11 17l4.5-4.5");
}

.zmp2owtdl {
  d: path("M4.75 3h14.5A1.75 1.75 0 0 1 21 4.75v1.5A1.75 1.75 0 0 1 19.25 8H4.75A1.75 1.75 0 0 1 3 6.25v-1.5A1.75 1.75 0 0 1 4.75 3M4.5 8v11.5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V8");
}

</style>
