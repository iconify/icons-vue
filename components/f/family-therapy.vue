<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m2goseb2m"/><path class="edeqwpiqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:family-therapy" /></template>
<style>
.edeqwpiqc {
  d: path("M6.5 11.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5.25 21.5V20a3.25 3.25 0 0 1 6.5 0v1.5M15 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-.5 6.5v-1a2 2 0 0 1 4 0v1");
}

.m2goseb2m {
  d: path("M2.5 10L12 2.5l9.5 7.5v11.5h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
