<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pqrrdkbgl"/><path class="hqymo8wxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arena-indoor" /></template>
<style>
.hqymo8wxy {
  d: path("M10 20.5V16a2 2 0 0 1 4 0v4.5");
}

.pqrrdkbgl {
  d: path("M2.5 20.5V11a9.5 6.5 0 0 1 19 0v9.5Zm0-9.5h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
