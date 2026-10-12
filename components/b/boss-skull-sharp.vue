<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dqdrsw51a"/><circle class="intacw5kh"/><circle class="mpjhfbbns"/><path class="sf5o6bb4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boss-skull-sharp" /></template>
<style>
.dqdrsw51a {
  d: path("M12 5c4 0 7 2.75 7 6.5c0 2.25-1 3.75-2.5 4.75V20h-9v-3.75C6 15.25 5 13.75 5 11.5C5 7.75 8 5 12 5Z");
}

.intacw5kh {
  cx: 9.25px;
  cy: 11.75px;
  r: 1.5px;
}

.mpjhfbbns {
  cx: 14.75px;
  cy: 11.75px;
  r: 1.5px;
}

.sf5o6bb4j {
  d: path("M10.5 17.75v1m3-1v1M6.75 7.5C4.5 6.75 3 5 3 2.75C4.25 4 6 4.75 8 5Zm10.5 0C19.5 6.75 21 5 21 2.75C19.75 4 18 4.75 16 5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
