<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="g-ncj10uz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:currency-peso" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.g-ncj10uz {
  d: path("M9.5 17.75V6.25h2.75a4 4 0 0 1 0 8H9.5M7 8.75h10.25M7 11.75h10.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
