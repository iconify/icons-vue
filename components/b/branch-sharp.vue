<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uzp2y2seh"/><path class="qcs0wvbgs"/><circle class="z2s2z540y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:branch-sharp" /></template>
<style>
.qcs0wvbgs {
  d: path("M8.5 17.75c.5 2 2 3.25 4 3.5c-.25-2-1.75-3.25-4-3.5Zm3.25-3c-1.75-1.25-2.5-3-2-5.25c1.75 1.25 2.5 3 2 5.25Zm4.7-4.8c-1.73-.86-2.65-2.31-2.52-4.38c1.73.86 2.65 2.31 2.52 4.38Zm-3.2 3.35l2.25.75l2.25-.75");
}

.uzp2y2seh {
  d: path("M2.75 18.75C9 17.5 14.5 13.5 19.5 5.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2s2z540y {
  cx: 19px;
  cy: 13.3px;
  r: 1.25px;
}

</style>
