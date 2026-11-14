<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y2f53cb5z"/><path class="o2z1ru1ci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fabric-folded" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2z1ru1ci {
  d: path("M9 3v12h12");
}

.y2f53cb5z {
  d: path("M3 3h6l12 12v4.5q-1.5 2-3 0t-3 0t-3 0t-3 0t-3 0t-3 0Z");
}

</style>
