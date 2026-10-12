<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cmgyb_itx"/><path class="kqj427b4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hunting-sharp" /></template>
<style>
.cmgyb_itx {
  d: path("M12 4a8 8 0 1 1 0 16a8 8 0 1 1 0-16m0-1.25V4m0 16v1.25M2.75 12H4m16 0h1.25");
}

.kqj427b4v {
  d: path("m10.5 11.75l-1.626-.739L9.25 8m.05 2.3l-1.55-.9m5.75 2.35l1.626-.739L14.75 8m-.05 2.3l1.55-.9M10 12.75v-1h4v1l-.9 3.6l-1.1 3.608l-1.1-3.608Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
