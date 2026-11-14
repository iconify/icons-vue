<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ib98ybatb"/><path class="k2mdc2baa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:expense" /></template>
<style>
.ib98ybatb {
  d: path("M5 3h14v18l-3.5-2l-3.5 2l-3.5-2L5 21Z");
}

.k2mdc2baa {
  d: path("M14.25 9.5C14 8.65 13.15 8.25 12 8.25c-1.4 0-2.25.7-2.25 1.75c0 2.1 4.5 1.2 4.5 4c0 1-.95 1.75-2.25 1.75c-1.2 0-2.05-.5-2.25-1.25M12 6.75v1.5m0 7.5v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
