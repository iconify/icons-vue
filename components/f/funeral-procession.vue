<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p16mkdbxb"/><path class="dm2vfybou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:funeral-procession" /></template>
<style>
.dm2vfybou {
  d: path("M4.5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2.5-9v4h3.5m-8-1.5v3M7 11.25h3");
}

.p16mkdbxb {
  d: path("M2.5 15.5v-5a3 3 0 0 1 3-3H13l3.5 4H20a1.5 1.5 0 0 1 1.5 1.5v2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
