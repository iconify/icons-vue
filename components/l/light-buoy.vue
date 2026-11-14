<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="glxjg91lc"/><path class="nzrh_zbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:light-buoy" /></template>
<style>
.glxjg91lc {
  d: path("M7.5 15a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzrh_zbqn {
  d: path("M12 7.5zA1.5 1.5 0 0 1 13.5 9a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 10.5 9A1.5 1.5 0 0 1 12 7.5M2.5 18h19M12 2.5v2.25M6.5 4.5L8 6m9.5-1.5L16 6");
}

</style>
