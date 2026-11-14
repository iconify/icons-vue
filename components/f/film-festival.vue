<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l_0hbe7wn"/><path class="aoh903b1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:film-festival" /></template>
<style>
.aoh903b1f {
  d: path("m12 7.5l.75 2.25l2.5.25l-1.75 1.5l.5 2.25l-2-1.25l-2 1.25l.5-2.25L8.75 10l2.5-.25Z");
}

.l_0hbe7wn {
  d: path("M10.25 17.75A6.5 6.5 0 0 1 8.75 6m-1 10.5L5 16.75m.5-4.25L3.25 11m3-2.75l-.5-2.75m8 12.25A6.5 6.5 0 0 0 15.25 6m1 10.5l2.75.25m-.5-4.25l2.25-1.5m-3-2.75l.5-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
