<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxa4vgbew"/><path class="fe9c5cduf"/><path class="ma7lidmyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gold-label-duotone-thin" /></template>
<style>
.fe9c5cduf {
  d: path("M3 7h13l5 5 -5 5H3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ma7lidmyb {
  d: path("m6 12 2 2 3.5 -3.5");
}

.sxa4vgbew {
  fill: currentColor;
  d: path("M3 7h13l5 5 -5 5H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
