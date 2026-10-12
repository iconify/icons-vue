<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="le-8dcpwo"/><circle class="gp0egaclj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:daisy-sharp" /></template>
<style>
.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.le-8dcpwo {
  d: path("M9.85 3.97a2.5 2.5 0 0 1 4.3 0a2.5 2.5 0 0 1 3.72 2.16a2.5 2.5 0 0 1 2.16 3.72a2.5 2.5 0 0 1 0 4.3a2.5 2.5 0 0 1-2.16 3.72a2.5 2.5 0 0 1-3.72 2.16a2.5 2.5 0 0 1-4.3 0a2.5 2.5 0 0 1-3.72-2.16a2.5 2.5 0 0 1-2.16-3.72a2.5 2.5 0 0 1 0-4.3a2.5 2.5 0 0 1 2.16-3.72a2.5 2.5 0 0 1 3.72-2.16Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
