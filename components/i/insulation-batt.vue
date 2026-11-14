<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gkuxeqbum"/><path class="fe4w1acdh"/><path class="qb21jcc6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insulation-batt" /></template>
<style>
.fe4w1acdh {
  d: path("M7 7c2.5-1 4.5 1 7.25 0S19 8 21.5 7v10H7");
}

.gkuxeqbum {
  d: path("M2 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qb21jcc6z {
  d: path("M5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9.75 0c1.25-1.25 2.75 1.25 4 0");
}

</style>
