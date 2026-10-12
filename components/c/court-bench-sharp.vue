<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e9-7-8-2z"/><path class="syvzvbbcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:court-bench-sharp" /></template>
<style>
.e9-7-8-2z {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

.syvzvbbcz {
  d: path("M8.5 10.25a3.5 3.5 0 0 1 7 0Zm-5.75 0h18.5v2.5H2.75zm1.5 2.5h15.5v8.5H4.25zm3.75 4h8");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
