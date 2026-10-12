<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><circle class="rp30yac0h"/><circle class="kz9_6bmgb"/><path class="seyu_709j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:astonished-face-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.kz9_6bmgb {
  cx: 15.25px;
  cy: 9.25px;
  r: 2.25px;
}

.rp30yac0h {
  cx: 8.75px;
  cy: 9.25px;
  r: 2.25px;
}

.seyu_709j {
  d: path("M12 13a1.75 2.75 0 1 1 0 5.5a1.75 2.75 0 1 1 0-5.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
