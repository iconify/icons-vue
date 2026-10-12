<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gek46gkeh"/><path class="bashc2b1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ear-side-sharp" /></template>
<style>
.bashc2b1l {
  d: path("M9.75 9.5c0-2.25 1.5-3.75 3.5-3.75s3.5 1.5 3.5 3.5c0 1.75-1.25 2.75-2 3.75l-.484.685l-.516 2.065");
}

.gek46gkeh {
  d: path("m8.5 4.5l2.1-1.75H13c3.75 0 6.25 2.75 6.25 6.25c0 2.75-1.25 4.25-2.5 5.5s-1.5 2.5-2 4.25l-.714 2.5H11.5c-1.75 0-3-1.25-3.25-3C7.5 15 6 12 6.25 9c.15-2 1-3.5 2.25-4.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
