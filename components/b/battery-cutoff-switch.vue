<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ggcbvwmhs"/><path class="o-bv1rb-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-cutoff-switch" /></template>
<style>
.ggcbvwmhs {
  d: path("M2.5 9H19v10H2.5Zm19 3.5v3");
}

.o-bv1rb-d {
  d: path("M9 14a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 9 14Zm2.75-1.5l3.5-8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
