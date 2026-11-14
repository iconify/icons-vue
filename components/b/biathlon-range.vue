<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rn25dz4co"/><path class="l93n8cnzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biathlon-range" /></template>
<style>
.l93n8cnzi {
  d: path("M9.5 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 6V17m-5 .5l-2.5 4m12.5-4l2.5 4");
}

.rn25dz4co {
  d: path("M6 8.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
