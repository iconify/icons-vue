<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pl9sa8bkx"/><path class="aud7wmw2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-peace" /></template>
<style>
.aud7wmw2x {
  d: path("M14.25 13.5c-1.5 0-3 .5-4 1.5m3.55-4.25v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pl9sa8bkx {
  d: path("M6.25 14V4.5a1.25 1.25 0 0 1 2.5 0V11h2.5V4.5a1.25 1.25 0 0 1 2.5 0v7h.15a1.6 1.6 0 0 1 3.2 0V16a5.25 5.25 0 0 1-5.25 5.25H10.8a4.5 4.5 0 0 1-4.5-4.5Z");
}

</style>
