<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bnsvg0bub"/><path class="aje206b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bulb-plant" /></template>
<style>
.aje206b6j {
  d: path("M12 12.75c-1.75 2-2.25 5-1.5 8.5");
}

.bnsvg0bub {
  d: path("M12 9c2 2.5 5.5 4 5.5 7.5c0 3-2.5 5-5.5 5s-5.5-2-5.5-5c0-3.5 3.5-5 5.5-7.5Zm0 0V3m0 3c2.5 0 4.5-1.5 4.5-3.5C14 2.5 12 4 12 6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
