<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g030okbxp"/><path class="ggd9ol9zz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flow-meter" /></template>
<style>
.g030okbxp {
  d: path("M6.5 6h11v12h-11Zm-4 3h4m-4 6h4m11-6h4m-4 6h4M9 12h6");
}

.ggd9ol9zz {
  d: path("M13.25 10.25L15 12l-1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
