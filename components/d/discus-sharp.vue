<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nmy8rwtcj"/><path class="uwov71btp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:discus-sharp" /></template>
<style>
.nmy8rwtcj {
  d: path("M4.75 13.5a8.25 4.75 0 1 0 16.5 0a8.25 4.75 0 1 0-16.5 0Z");
}

.uwov71btp {
  d: path("M7.75 13.5a5.25 1.75 0 1 0 10.5 0a5.25 1.75 0 1 0-10.5 0Zm-5-2.25C4.5 7.25 8.5 5.5 13 5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
