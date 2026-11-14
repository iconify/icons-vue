<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f__zl1yhs"/><path class="sz5sxluht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charity-sleepout" /></template>
<style>
.f__zl1yhs {
  d: path("M12.941 18.5H2.5l7.5-15l5.29 10.581");
}

.sz5sxluht {
  d: path("m8.5 18.5l1.5-4l1.5 4m7.25-2.75a3 3 0 1 0 3 3a2.75 2.75 0 0 1-3-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
