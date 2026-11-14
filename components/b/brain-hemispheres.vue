<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x4z5_hbov"/><path class="f1x9odx_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brain-hemispheres" /></template>
<style>
.f1x9odx_f {
  d: path("M6.5 7.5c1.5.5 2 2 1 3.5m-1 5.5c1.25-.75 2-2 1.25-3m9.75-6c-1.5.5-2 2-1 3.5m1 5.5c-1.25-.75-2-2-1.25-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x4z5_hbov {
  d: path("M10.75 2.75C6 2.75 3.5 6.75 3.5 12s2.5 9.25 7.25 9.25Zm2.5 0c4.75 0 7.25 4 7.25 9.25s-2.5 9.25-7.25 9.25Z");
}

</style>
