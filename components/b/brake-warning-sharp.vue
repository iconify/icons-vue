<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="o_ly6ursf"/><path class="rm2ogybnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brake-warning-sharp" /></template>
<style>
.o_ly6ursf {
  cx: 12px;
  cy: 12px;
  r: 6.75px;
}

.rm2ogybnb {
  d: path("M12 8.75v3.75m0 2.75v.01M4.25 6.5a12 12 0 0 0 0 11m15.5-11a12 12 0 0 1 0 11");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
