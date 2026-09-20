<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tbfv-yd2s"/><path class="jm7jgyogs"/><path class="vrzeiketi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dental-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jm7jgyogs {
  d: path("M4 6a4 4 0 0 1 5 2 4 4 0 0 1 5 -2c2 4 0 13 -2.5 13C10 19 10 13 9 13s-1 6 -2.5 6C4 19 2 10 4 6");
}

.tbfv-yd2s {
  fill: currentColor;
  d: path("M4 6a4 4 0 0 1 5 2 4 4 0 0 1 5 -2c2 4 0 13 -2.5 13C10 19 10 13 9 13s-1 6 -2.5 6C4 19 2 10 4 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vrzeiketi {
  d: path("m16 15 2 2 4 -4");
}

</style>
