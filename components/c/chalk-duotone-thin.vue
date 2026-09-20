<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfw-_qbdb"/><path class="wy_ebz_tz"/><path class="p8527rbyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chalk-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p8527rbyx {
  d: path("m7 15 4 4");
}

.rfw-_qbdb {
  fill: currentColor;
  d: path("M5 17 15 7l4 4L9 21Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wy_ebz_tz {
  d: path("M5 17 15 7l4 4L9 21Z");
}

</style>
