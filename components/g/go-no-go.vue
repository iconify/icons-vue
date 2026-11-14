<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i1bxdt15t"/><path class="fgfgys6fj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:go-no-go" /></template>
<style>
.fgfgys6fj {
  d: path("M9.5 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm0 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.i1bxdt15t {
  d: path("M9.5 2.5h5a3 3 0 0 1 3 3v13a3 3 0 0 1-3 3h-5a3 3 0 0 1-3-3v-13a3 3 0 0 1 3-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
