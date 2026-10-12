<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e3eq0_bdx"/><circle class="ix0sepbgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:interrobang-sharp" /></template>
<style>
.e3eq0_bdx {
  d: path("M7.75 8a4.25 4.25 0 1 1 6.6 3.55L12 13.061v2.189m0-8.75v8.75");
}

.ix0sepbgl {
  cx: 12px;
  cy: 19.5px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
