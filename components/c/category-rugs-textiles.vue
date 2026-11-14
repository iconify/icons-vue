<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h8rgc_6ms"/><path class="telv2wbvr"/><path class="jobdllboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-rugs-textiles" /></template>
<style>
.h8rgc_6ms {
  d: path("M16.5 8h-12v11h12");
}

.jobdllboo {
  d: path("M16.5 12.75c.25 0 .5-.25.75 0c.25 0 .75.5.75.75c.25.25.25 1 0 1.5c-.25.25-1 .75-1.5.75c-.5.25-1.5 0-2-.25c-.5-.5-1-1.25-1.25-2c0-.75.25-1.75.75-2.5s1.5-1.25 2.5-1.5c1 0 2.25.25 3 1c.75.5 1.5 2 1.75 3c0 1-.25 2.75-1.25 3.5c-.75 1-3 1.75-3.5 2M6.75 8v11M9 8v11m-6.5-9h2m-2 3.5h2m-2 3.5h2");
}

.telv2wbvr {
  d: path("M11 13.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
