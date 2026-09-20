<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mwf5pf3ps"/><path class="o1d_6eb1p"/><path class="ghpezkxlh"/><path class="ffv1x3til"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:body-temperature-outline-thin" /></template>
<style>
.ffv1x3til {
  d: path("M15 4a6 6 0 0 1 0 12");
}

.ghpezkxlh {
  d: path("M15 7a3 3 0 0 1 0 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mwf5pf3ps {
  d: path("M9 4v11");
}

.o1d_6eb1p {
  d: path("M6 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
