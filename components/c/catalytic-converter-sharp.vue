<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h3_frbcod"/><path class="wccd07bsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:catalytic-converter-sharp" /></template>
<style>
.h3_frbcod {
  d: path("M3.5 10.75H6l.35-.66l1.3-2.43L8 7h8l.35.66l1.3 2.43l.35.66h3.25v2.5H18l-.35.66l-1.3 2.43L16 17H8l-.35-.66l-1.3-2.43l-.35-.66H2.75v-2.5z");
}

.wccd07bsz {
  d: path("M9.5 9.75h5v4.5h-5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
