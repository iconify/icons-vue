<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cm3un8cuh"/><path class="hugua6bkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-crown" /></template>
<style>
.cm3un8cuh {
  d: path("M2.5 14.75a9.5 5.25 0 1 0 19 0a9.5 5.25 0 1 0-19 0Z");
}

.hugua6bkf {
  d: path("M12.75 6.25a1 1 0 1 1 .5 1.5A1 1 0 1 1 12 8.5a1 1 0 1 1-1.25-.75a1 1 0 1 1 .5-1.5a1 1 0 1 1 1.5 0ZM5.25 8.5a.75.75 0 1 1 .5 1a.75.75 0 1 1-1 .75a.75.75 0 1 1-1-.75a.75.75 0 1 1 .5-1a.75.75 0 1 1 1 0Zm14.5 0a.75.75 0 1 1 .5 1a.75.75 0 1 1-1 .75a.75.75 0 1 1-1-.75a.75.75 0 1 1 .5-1a.75.75 0 1 1 1 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
