<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ck7-3h_jx"/><path class="etc7zccbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kidneys-sharp" /></template>
<style>
.ck7-3h_jx {
  d: path("M15 4.5c-3.5-2.5-9.75-.75-10.25 6C4.25 17 9.5 21 13.5 19.75c2.5-.75 2.5-3.5 1-5L12.75 13l1.75-1.75c1.75-1.75 2.75-4.75.5-6.75Z");
}

.etc7zccbc {
  d: path("M15.5 13h4.75v8.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
