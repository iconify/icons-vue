<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-0ii1bwy"/><path class="j0qit8bpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bunny-ears" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j0qit8bpa {
  d: path("M6.75 13.75C4.75 9 4.75 2.5 7.5 2.5S10.75 8 10 12.25m7.25 1.5c2-4.75 2-11.25-.75-11.25S13.25 8 14 12.25");
}

.r-0ii1bwy {
  d: path("M3.5 20.5a8.5 8.5 0 0 1 17 0");
}

</style>
