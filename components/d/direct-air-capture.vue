<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sasp0tdje"/><path class="vyco1ya4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:direct-air-capture" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sasp0tdje {
  d: path("M12 2.5h6A3.5 3.5 0 0 1 21.5 6v12a3.5 3.5 0 0 1-3.5 3.5h-6A3.5 3.5 0 0 1 8.5 18V6A3.5 3.5 0 0 1 12 2.5");
}

.vyco1ya4k {
  d: path("M11.25 12a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M15 12h.01M2.5 12h6M6.25 9.75L8.5 12l-2.25 2.25");
}

</style>
