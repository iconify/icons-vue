<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="it_1vublq"/><path class="g7r2n3-ke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corner-left-down" /></template>
<style>
.g7r2n3-ke {
  d: path("m13 15.5l-3.75 3.75L5.5 15.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it_1vublq {
  d: path("M19.75 4.25h-8a2.5 2.5 0 0 0-2.5 2.5v12.5");
}

</style>
