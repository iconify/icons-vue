<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v0678_blx"/><path class="x4yi1rozh"/><path class="mj2w05jsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coverage-overlap" /></template>
<style>
.mj2w05jsa {
  d: path("M14.75 15L16 9l1.25 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0678_blx {
  d: path("M3 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.x4yi1rozh {
  d: path("M11 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm-4.25 3L8 9l1.25 6");
}

</style>
