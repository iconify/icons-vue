<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4ixodbit"/><path class="p3gwist-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cup-with-straw" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p3gwist-g {
  d: path("M12 7V4l3-1.5");
}

.u4ixodbit {
  d: path("m7 11l1.5 10.5h7L17 11M6 11a6 4 0 0 1 12 0Z");
}

</style>
