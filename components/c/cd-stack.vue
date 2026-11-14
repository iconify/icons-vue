<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kptqo7d0h"/><path class="grlkcu0bg"/><path class="uh4b5abpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cd-stack" /></template>
<style>
.grlkcu0bg {
  d: path("M17.471 14.464a6 6 0 1 1-7.935-7.935");
}

.kptqo7d0h {
  d: path("M9 9a6 6 0 1 0 12 0A6 6 0 1 0 9 9Z");
}

.uh4b5abpb {
  d: path("M14.471 17.464a6 6 0 1 1-7.935-7.935M13.25 9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
