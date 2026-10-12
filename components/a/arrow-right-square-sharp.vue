<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nciaxcb6w"/><path class="it38sin7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-right-square-sharp" /></template>
<style>
.it38sin7q {
  d: path("M7.5 12h8.75M12.5 8.25L16.25 12l-3.75 3.75");
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
