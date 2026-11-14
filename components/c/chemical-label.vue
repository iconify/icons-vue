<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tcm1-8vxk"/><path class="e1om8-d9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chemical-label" /></template>
<style>
.e1om8-d9f {
  d: path("m12 11l3.5 3.5L12 18l-3.5-3.5Z");
}

.tcm1-8vxk {
  d: path("M10 2.5h4v5.25a7 7 0 1 1-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
