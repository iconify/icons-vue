<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j0r-5jaco"/><path class="r5nwp2qpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aquarium-tunnel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j0r-5jaco {
  d: path("M2.5 3v16a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2V3");
}

.r5nwp2qpa {
  d: path("M5.5 21v-3a6.5 3 0 0 1 13 0v3m-2-10.5c-1.5-2.25-4.5-2.25-6.25 0L7.5 8.75v3.5l2.75-1.75c1.75 2.25 4.75 2.25 6.25 0");
}

</style>
