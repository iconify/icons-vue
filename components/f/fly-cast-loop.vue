<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oh_7r2dnp"/><path class="sdoc9bcgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fly-cast-loop" /></template>
<style>
.oh_7r2dnp {
  d: path("M3.5 21.5Q8 9 15 4.5m0 0c3-2 6.5-1.5 6.5 2s-5.5 4.5-8 4");
}

.sdoc9bcgr {
  d: path("M5.25 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
