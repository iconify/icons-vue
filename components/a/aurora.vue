<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jgthrmbrw"/><path class="fhgetxbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aurora" /></template>
<style>
.fhgetxbbn {
  d: path("M6.5 6.5c-2 2 2 4 0 6s2 4 0 5.5M12 5.5c-2 2.25 2 4.5 0 6.75s2 4.5 0 6.75c-1 1-.5 1.5 0 2m5.5-14.5c-2 2 2 4 0 6c-1 1-.5 2 0 2.5m2.25-13v2.5M18.5 3.25H21");
}

.jgthrmbrw {
  d: path("M3 8q9-5 18 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
