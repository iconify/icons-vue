<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ix24vfbgy"/><path class="tcvms5bwh"/><path class="pmgbi8bhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:citrus-net" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ix24vfbgy {
  d: path("M10.75 5.5c-4.5 2-6.5 5.5-6.5 9.5v2a4.25 4.25 0 0 0 4.25 4.25h7A4.25 4.25 0 0 0 19.75 17v-2c0-4-2-7.5-6.5-9.5ZM9.5 2.75L12 5.5l2.5-2.75");
}

.pmgbi8bhs {
  d: path("M9.5 11.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.tcvms5bwh {
  d: path("M7 16a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
