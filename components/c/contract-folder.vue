<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ownep8bqj"/><path class="hlie_gb9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contract-folder" /></template>
<style>
.hlie_gb9s {
  d: path("M2.5 10a2 2 0 0 1 2-2h2l2 2h11a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Zm13.25-7.5v3.75h3.75");
}

.ownep8bqj {
  d: path("M11.25 10V2.5h4.5l3.75 3.75V10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
