<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a733ohy6q"/><path class="svfgbfbfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:capitol" /></template>
<style>
.a733ohy6q {
  d: path("M2.75 21.25v-6a1 1 0 0 1 1-1h3.5V12.5H8a4 4 0 0 1 8 0h.75v1.75h3.5a1 1 0 0 1 1 1v6Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.svfgbfbfl {
  d: path("M12 8.5V2.75h3m-5.5 14v2.5m2.5-2.5v2.5m2.5-2.5v2.5M5.5 17v2m13-2v2");
}

</style>
