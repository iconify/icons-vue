<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xurtju55z"/><path class="mwqze2bvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garage-opener" /></template>
<style>
.mwqze2bvz {
  d: path("M10 15.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-.5-9.25a4.5 4.5 0 0 1 5 0m-6.75-2.5a7.5 7.5 0 0 1 8.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xurtju55z {
  d: path("M8 9h8a1 1 0 0 1 1 1v10.5a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1Z");
}

</style>
