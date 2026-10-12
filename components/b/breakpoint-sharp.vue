<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="utc29-bcy"/><path class="l2_9_1byq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:breakpoint-sharp" /></template>
<style>
.l2_9_1byq {
  d: path("M13.25 6.75h7m-7 5.25h7m-7 5.25h4.5");
}

.utc29-bcy {
  cx: 7px;
  cy: 12px;
  r: 3.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
