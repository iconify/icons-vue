<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u6dhvh83n"/><path class="swdzecb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kitting-cart" /></template>
<style>
.swdzecb9o {
  d: path("M7 5h4.5v5.5H7Zm6.5 0H18v5.5h-4.5Z");
}

.u6dhvh83n {
  d: path("M3.5 3v14h16m-16-6.5h16M4.5 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm11 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
