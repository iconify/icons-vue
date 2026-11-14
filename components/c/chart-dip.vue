<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w6tq9zu6e"/><path class="rsgm0wzrl"/><path class="iac65qc8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-dip" /></template>
<style>
.iac65qc8y {
  d: path("M12 17.5v4m-2-2l2 2l2-2");
}

.rsgm0wzrl {
  fill: currentColor;
  d: path("M10 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6tq9zu6e {
  d: path("M2.5 4C6 4 8.5 14 12 14s6-10 9.5-10");
}

</style>
