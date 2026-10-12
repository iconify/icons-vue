<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ug1uahwej"/><circle class="fxwnb7vgp"/><path class="hspgb-b5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-thermometer-sharp" /></template>
<style>
.fxwnb7vgp {
  cx: 5px;
  cy: 19px;
  r: 2px;
}

.hspgb-b5j {
  d: path("m12 12l2.5-2.5");
}

.ug1uahwej {
  d: path("m8.23 12.23l7.5-7.5a2.5 2.5 0 0 1 3.54 3.54l-7.5 7.5a2.5 2.5 0 0 1-3.54-3.54Zm0 3.54l-1.82 1.82");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
