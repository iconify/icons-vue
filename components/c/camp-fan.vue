<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l5u3cc29f"/><path class="nc9hvugyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camp-fan" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5u3cc29f {
  d: path("M2.5 8.75a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m6.5 6.5v5.25m-4.5 0h7.2");
}

.nc9hvugyf {
  d: path("M9 4.75v4l-3.5 2m3.5-2l3.5 2m3 5.75h4a1 1 0 0 1 1 1v.25h1v2h-1V20a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-2.5a1 1 0 0 1 1-1");
}

</style>
