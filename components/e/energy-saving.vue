<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ungkwibod"/><path class="nee-70r0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:energy-saving" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nee-70r0o {
  d: path("m11 7.75l-3 4.5h3.5l-2.25 4M19 4.75v14m-2-2l2 2l2-2");
}

.ungkwibod {
  cx: 9.75px;
  cy: 12px;
  r: 7px;
}

</style>
