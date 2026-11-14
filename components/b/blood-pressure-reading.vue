<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rvskad8kn"/><path class="cm_f3bbsw"/><path class="a2-5zzbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blood-pressure-reading" /></template>
<style>
.a2-5zzbpt {
  d: path("M12 16.5v3m-4 1h8");
}

.cm_f3bbsw {
  fill: currentColor;
  d: path("M17 13s-2.25-1.5-2.25-3.25c0-.75.6-1.25 1.25-1.25c.4 0 .75.25 1 .5c.25-.25.6-.5 1-.5c.65 0 1.25.5 1.25 1.25C19.25 11.5 17 13 17 13Z");
}

.rvskad8kn {
  d: path("M2.5 3h19v13.5h-19Zm3 4h6m-4 5.5h4m2.75-7l-2 8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
