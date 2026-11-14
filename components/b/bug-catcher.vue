<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="awqa55bhl"/><path class="a_hpiwbkb"/><path class="xf2-w248t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bug-catcher" /></template>
<style>
.a_hpiwbkb {
  d: path("M9.25 16.25a2.75 3.5 0 1 0 5.5 0a2.75 3.5 0 1 0-5.5 0Z");
}

.awqa55bhl {
  d: path("M5.5 2.5h13v4h-13Zm1 4V8c-2 .5-3 2-3 4v7A2.5 2.5 0 0 0 6 21.5h12a2.5 2.5 0 0 0 2.5-2.5v-7c0-2-1-3.5-3-4V6.5m-5.5-2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xf2-w248t {
  d: path("M10.75 11.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM7 14l2.25 1M7 18.75l2.25-1.25M17 14l-2.25 1M17 18.75l-2.25-1.25");
}

</style>
