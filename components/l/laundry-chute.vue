<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xtvuoqbmv"/><path class="qzrr52x1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:laundry-chute" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qzrr52x1z {
  d: path("M10.75 5.5h2.5A1.75 1.75 0 0 1 15 7.25v1A1.75 1.75 0 0 1 13.25 10h-2.5A1.75 1.75 0 0 1 9 8.25v-1a1.75 1.75 0 0 1 1.75-1.75M12 13v5.75m-2.5-2.5l2.5 2.5l2.5-2.5");
}

.xtvuoqbmv {
  d: path("M10.75 2.5h2.5a5.25 5.25 0 0 1 5.25 5.25v8.5a5.25 5.25 0 0 1-5.25 5.25h-2.5a5.25 5.25 0 0 1-5.25-5.25v-8.5a5.25 5.25 0 0 1 5.25-5.25");
}

</style>
