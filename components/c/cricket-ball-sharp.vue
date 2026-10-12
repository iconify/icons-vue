<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="q7_rzcclg"/><path class="jwya3guqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cricket-ball-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.jwya3guqr {
  d: path("M9.5 3.25c-1.5 3-2 6-1.9 8.4m1.9 9.1l-2.048-2.731l.148-2.669");
}

.q7_rzcclg {
  d: path("M3.05 10.6c5.9 2 12 2 17.9 0l.05 2.9c-5.95 2-12.05 2-18 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
