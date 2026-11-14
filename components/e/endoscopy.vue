<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d2kfgabxw"/><path class="i3scrsbcw"/><path class="ns-vucrcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:endoscopy" /></template>
<style>
.d2kfgabxw {
  d: path("M11 7.5c2-1.5 8.5-1.5 8.5 5c0 5-4 8-8.5 8c-4 0-6.5-2.5-6.5-5.5c0-1.5 1-2.5 2.5-2.5c2 0 2-2.5 2-3.5Zm-1.5-5v6.25");
}

.i3scrsbcw {
  d: path("M12.5 2.5v7c0 1.5 1 2.75 2.5 3.25");
}

.ns-vucrcp {
  fill: currentColor;
  d: path("M14.5 13a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
