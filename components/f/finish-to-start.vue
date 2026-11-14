<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mh6x_mbpz"/><path class="zcfv3tb9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:finish-to-start" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mh6x_mbpz {
  d: path("M4.75 4h5A2.25 2.25 0 0 1 12 6.25A2.25 2.25 0 0 1 9.75 8.5h-5A2.25 2.25 0 0 1 2.5 6.25A2.25 2.25 0 0 1 4.75 4m9.5 11.5h5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 19.25 20h-5A2.25 2.25 0 0 1 12 17.75a2.25 2.25 0 0 1 2.25-2.25M12 6.25h3.5v9.25");
}

.zcfv3tb9a {
  d: path("m13.75 13.75l1.75 1.75l1.75-1.75");
}

</style>
