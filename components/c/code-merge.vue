<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uk3n2uz6m"/><path class="wy7_75u1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-merge" /></template>
<style>
.uk3n2uz6m {
  d: path("M6.5 7.75v8.5m0-8.5c0 4.75 4 8.75 8.75 8.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wy7_75u1b {
  d: path("M4.25 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm0 13a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11-2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

</style>
