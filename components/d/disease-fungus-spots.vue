<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fbjddobdf"/><path class="jepkukcjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:disease-fungus-spots" /></template>
<style>
.fbjddobdf {
  d: path("M3.5 20.5C2 8 8 2 20.5 3.5C22 16 16 22 3.5 20.5Z");
}

.jepkukcjj {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5-4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-8.75 9a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
