<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="b36epmbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-cool" /></template>
<style>
.b36epmbyy {
  d: path("M6 9h4.75v1.25a2.38 2.38 0 0 1-4.75 0Zm7.25 0H18v1.25a2.38 2.38 0 0 1-4.75 0Zm-2.5 0h2.5M9.5 15.75c1.75.75 3.75.5 5-.75");
}

.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
