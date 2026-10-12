<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j18zj9mqg"/><circle class="tdcmh-bcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baseball-bat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j18zj9mqg {
  d: path("m10.39 14.89l8.13-5.87a2.5 2.5 0 0 0-3.54-3.54l-5.87 8.13Zm-.64-.64l-5 5M3.5 18L6 20.5");
}

.tdcmh-bcw {
  cx: 6.75px;
  cy: 6.75px;
  r: 2.75px;
}

</style>
