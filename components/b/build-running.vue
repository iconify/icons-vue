<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ehtgz1bpt"/><path class="a0ou40b7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:build-running" /></template>
<style>
.a0ou40b7a {
  d: path("M19.25 3.75V8H15M4.75 20.25V16H9");
}

.ehtgz1bpt {
  d: path("M4.5 9.25A8 8 0 0 1 19 8m.5 6.75A8 8 0 0 1 5 16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
