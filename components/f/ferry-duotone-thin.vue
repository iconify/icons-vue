<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jh-r4db2e"/><path class="r0ugme01d"/><path class="tz2pshf0g"/><path class="vrecxx6kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ferry-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jh-r4db2e {
  fill: currentColor;
  d: path("M2 15h20l-5 5H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r0ugme01d {
  d: path("M2 15h20l-5 5H7Z");
}

.tz2pshf0g {
  d: path("M7 15V9h10v6");
}

.vrecxx6kh {
  d: path("M9 6h6");
}

</style>
