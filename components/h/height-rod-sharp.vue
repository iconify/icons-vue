<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n-vkuqshl"/><circle class="og3k95x3a"/><path class="u4qq3nbez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:height-rod-sharp" /></template>
<style>
.n-vkuqshl {
  d: path("M13.5 2.75h3v18.5h-3zm0 6.75H15M13.5 13h1m-1 3.5H15");
}

.og3k95x3a {
  cx: 7px;
  cy: 9px;
  r: 2px;
}

.u4qq3nbez {
  d: path("M3.5 21.25v-4.5a3.5 3.5 0 0 1 7 0v4.5Zm0 0h17M4.5 7h9");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
