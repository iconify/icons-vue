<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="p51kdhlwz"/><path class="p2g-rb2fg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-nauseous-sharp" /></template>
<style>
.p2g-rb2fg {
  d: path("M6.75 10H9m2.5 0h2.25m-7 5.25l.875-.875l.875.875l.875.875l.875-.875l.875-.875l.875.875l.875.875l.875-.875m5.5-12.5c1 1.4 1.75 2.4 1.75 3.4a1.75 1.75 0 0 1-3.5 0c0-1 .75-2 1.75-3.4Z");
}

.p51kdhlwz {
  cx: 10.25px;
  cy: 12.75px;
  r: 7.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
