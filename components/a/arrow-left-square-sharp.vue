<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nciaxcb6w"/><path class="rpiz0hb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-left-square-sharp" /></template>
<style>
.nciaxcb6w {
  d: path("M3.25 3.25h17.5v17.5H3.25z");
}

.rpiz0hb3i {
  d: path("M16.5 12H7.75m3.75 3.75L7.75 12l3.75-3.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
