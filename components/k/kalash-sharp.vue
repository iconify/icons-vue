<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="g828vzbqg"/><path class="vp1v9mb_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kalash-sharp" /></template>
<style>
.g828vzbqg {
  cx: 12px;
  cy: 5px;
  r: 2.25px;
}

.vp1v9mb_d {
  d: path("M9 10c-2 .25-4-.5-5-2.25C6 7.25 8 8 9 10Zm6 0c2 .25 4-.5 5-2.25c-2-.5-4 .25-5 2.25Zm-6 .25h6V11c2.5 1 4.25 3 4.25 5.25c0 2.5-2 4.75-4.75 4.75h-5c-2.75 0-4.75-2.25-4.75-4.75C4.75 14 6.5 12 9 11Zm-1.75 5h9.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
