<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wr_x3vb4r"/><path class="l3c8gmbjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:can-seamer" /></template>
<style>
.l3c8gmbjd {
  d: path("M14.25 6a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM5 8h10m2-2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wr_x3vb4r {
  d: path("m5 8l1.5-3.5h7L15 8v12a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 5 20Z");
}

</style>
