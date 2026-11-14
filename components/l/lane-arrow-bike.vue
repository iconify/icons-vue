<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mw284tzem"/><path class="tblunablv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lane-arrow-bike" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mw284tzem {
  d: path("M12 9.5v-7M8.5 6L12 2.5L15.5 6M3 17a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m11 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.tblunablv {
  d: path("m6.5 17l3-4.5h6l2 4.5");
}

</style>
