<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="babiizbmu"/><circle class="m_ubk9bxa"/><circle class="vk0oucc3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lawn-mower-sharp" /></template>
<style>
.babiizbmu {
  d: path("m8 11.75l-3.25-8.5H3m1.25 13v-4.5h15v4.5Z");
}

.m_ubk9bxa {
  cx: 7px;
  cy: 18.75px;
  r: 2.5px;
}

.vk0oucc3w {
  cx: 16.75px;
  cy: 18.75px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
