<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zdaa52bks"/><path class="o6a500beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bin-location-sharp" /></template>
<style>
.o6a500beq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zdaa52bks {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13.75h15.5v7.5H4.25zm5.5 3.75h4.5M12 11C9.83 8.83 8.75 7.58 8.75 6a3.25 3.25 0 0 1 6.5 0c0 1.58-1.08 2.83-3.25 5Z");
}

</style>
