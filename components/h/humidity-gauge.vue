<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yp0_tkb1w"/><path class="bfox4xpxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:humidity-gauge" /></template>
<style>
.bfox4xpxs {
  d: path("M12 12.75S9.75 15.5 9.75 17a2.25 2.25 0 0 0 4.5 0c0-1.5-2.25-4.25-2.25-4.25Zm0 0L15.75 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yp0_tkb1w {
  d: path("M2.5 14.25a9.5 9.5 0 0 1 19 0");
}

</style>
