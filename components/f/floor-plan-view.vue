<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sb3kunsea"/><path class="qqipvh25z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:floor-plan-view" /></template>
<style>
.qqipvh25z {
  d: path("M16 9a4 4 0 0 1-4 4m0-4h4");
}

.sb3kunsea {
  d: path("M3 3h18v18H3Zm9 0v6m0 4v8m-9-9h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
