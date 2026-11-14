<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zdu2wdiqn"/><path class="gww0mxbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camping-lantern" /></template>
<style>
.gww0mxbnz {
  d: path("M12 11.5c1.25 1.25 1.75 2 1.75 3a1.75 1.75 0 0 1-3.5 0c0-1 .5-1.75 1.75-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdu2wdiqn {
  d: path("M9.5 6V4.5a2.5 2.5 0 0 1 5 0V6M6 8.5L8.5 6h7L18 8.5Zm2.5 0h7A1.5 1.5 0 0 1 17 10v7.5a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 17.5V10a1.5 1.5 0 0 1 1.5-1.5M7.25 19h9.5A1.25 1.25 0 0 1 18 20.25a1.25 1.25 0 0 1-1.25 1.25h-9.5A1.25 1.25 0 0 1 6 20.25A1.25 1.25 0 0 1 7.25 19");
}

</style>
