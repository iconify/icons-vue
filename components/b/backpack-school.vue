<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k__fngbun"/><path class="of_ixpzqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:backpack-school" /></template>
<style>
.k__fngbun {
  d: path("M7.5 5.5h9A2.5 2.5 0 0 1 19 8v11a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 19V8a2.5 2.5 0 0 1 2.5-2.5Zm2 0v-1a2.5 2.5 0 0 1 5 0v1");
}

.of_ixpzqs {
  d: path("M8 13.5h8v5H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
