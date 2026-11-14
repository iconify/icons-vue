<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eh2wwl3wp"/><path class="ppfywmeoi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:descaler" /></template>
<style>
.eh2wwl3wp {
  d: path("M11 2.5h2A1.5 1.5 0 0 1 14.5 4A1.5 1.5 0 0 1 13 5.5h-2A1.5 1.5 0 0 1 9.5 4A1.5 1.5 0 0 1 11 2.5m-1 3v2l-4 3V20a1.5 1.5 0 0 0 1.5 1.5h9A1.5 1.5 0 0 0 18 20v-9.5l-4-3v-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ppfywmeoi {
  d: path("m13.33 14.549l.525 1.007a1.5 1.5 0 0 1-1.329 2.194h-1.052a1.5 1.5 0 0 1-1.329-2.194l.525-1.007a1.5 1.5 0 0 1 2.66 0");
}

</style>
