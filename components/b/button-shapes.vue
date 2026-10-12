<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a1p0_acds"/><path class="geui7dbst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:button-shapes" /></template>
<style>
.a1p0_acds {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 6.25px;
  rx: 5.75px;
}

.geui7dbst {
  d: path("m7.25 13.25l2.25-4.5l2.25 4.5M8 11.75h3m2.25 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m3-1.5v3m-9 2h9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
