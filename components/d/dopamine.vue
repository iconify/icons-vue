<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w1y1ksb9s"/><path class="i72xm7ypi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dopamine" /></template>
<style>
.i72xm7ypi {
  d: path("M7 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1y1ksb9s {
  d: path("m9 6.5l4.75 2.75v5.5L9 17.5l-4.75-2.75v-5.5Zm4.75 2.75l3-1.75l3 1.75v3.25");
}

</style>
