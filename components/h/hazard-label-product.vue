<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xh15i7v9w"/><path class="hq1_f5beh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hazard-label-product" /></template>
<style>
.hq1_f5beh {
  d: path("m18 13.75l4 4l-4 4l-4-4Zm0 2.75v2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xh15i7v9w {
  d: path("M13.774 21.5H5v-10c0-2 1.5-3 3.5-3.5V5.5h6V8c1.455.364 2.645.992 3.186 2.077M8 2.5h7v3H8Zm-3 11h9.3");
}

</style>
