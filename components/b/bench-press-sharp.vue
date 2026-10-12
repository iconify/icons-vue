<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dk0cgtklm"/><circle class="mf93ukbgu"/><path class="hniznjo0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bench-press-sharp" /></template>
<style>
.dk0cgtklm {
  d: path("M2.75 6h18.5m-17-2.75h2v5.5h-2zm13.5 0h2v5.5h-2z");
}

.hniznjo0b {
  d: path("M7.5 12.5h7m-5.5 0V6m5.5 6.5l3.5 2v6.75M4.75 16h11M6.5 16v5.25");
}

.mf93ukbgu {
  cx: 5px;
  cy: 12.25px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
