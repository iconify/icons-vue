<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e9-7-8-2z"/><path class="zhdirccur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:firefly-sharp" /></template>
<style>
.e9-7-8-2z {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zhdirccur {
  d: path("M10.25 9c-2.75-2-5.5-2.25-7.5-.5c1 2.75 4 3.5 7.5.5Zm3.5 0c2.75-2 5.5-2.25 7.5-.5c-1 2.75-4 3.5-7.5.5ZM12 11.5c1.75 0 3 2 3 4.5s-1.25 4.5-3 4.5s-3-2-3-4.5s1.25-4.5 3-4.5Zm-5.25 5.75l-2 1.25m12.5-1.25l2 1.25");
}

</style>
