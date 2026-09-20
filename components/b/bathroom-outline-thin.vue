<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y_ufkmm9t"/><path class="d-a_pubdj"/><path class="anqaqozxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bathroom-outline-thin" /></template>
<style>
.anqaqozxz {
  d: path("M15 4h6");
}

.d-a_pubdj {
  d: path("M18 4v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_ufkmm9t {
  d: path("M3 12h18v4a4 4 0 0 1 -4 4H7a4 4 0 0 1 -4 -4Z");
}

</style>
