<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="trpl5bzaw"/><path class="py5-wbsfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beach-cruiser" /></template>
<style>
.py5-wbsfx {
  d: path("M6.5 14.5H11q2-5.5 4.5-6l2 6M7.5 8h3M9 8l-2.5 6.5m9-6l.5-3q-1.5-.5-3.25.5");
}

.trpl5bzaw {
  d: path("M2.5 14.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
