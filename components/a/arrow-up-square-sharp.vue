<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nciaxcb6w"/><path class="fj1uodb3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-up-square-sharp" /></template>
<style>
.fj1uodb3h {
  d: path("M12 16.5V7.75M8.25 11.5L12 7.75l3.75 3.75");
}

.nciaxcb6w {
  d: path("M3.25 3.25h17.5v17.5H3.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
