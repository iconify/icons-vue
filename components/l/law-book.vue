<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l3qt-la5f"/><path class="hd1t0j2zq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:law-book" /></template>
<style>
.hd1t0j2zq {
  d: path("M19.25 16.25h-12a2.5 2.5 0 0 0-2.5 2.5M8.75 7h6.5m-6.5 3.25h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3qt-la5f {
  d: path("M19.25 2.75v18.5h-12a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5Z");
}

</style>
