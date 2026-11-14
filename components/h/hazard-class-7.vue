<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dh2jzoboc"/><path class="ned3vpbbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hazard-class-7" /></template>
<style>
.dh2jzoboc {
  d: path("m12 2l10 10l-10 10L2 12Z");
}

.ned3vpbbx {
  d: path("m13 13.75l1.5 2.5a5 5 0 0 1-5 0l1.5-2.5a2 2 0 0 0 2 0ZM10 12H7a5 5 0 0 1 2.5-4.25l1.5 2.5A2 2 0 0 0 10 12Zm3-1.75l1.5-2.5A5 5 0 0 1 17 12h-3a2 2 0 0 0-1-1.75ZM12 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
