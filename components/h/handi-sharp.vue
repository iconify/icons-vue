<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="miscaab_g"/><path class="mcb9cpb1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:handi-sharp" /></template>
<style>
.mcb9cpb1b {
  d: path("M7.5 10.25h9c2.25 1.25 3.75 3.25 3.75 5.5c0 3.25-3.5 5.5-8.25 5.5S3.75 19 3.75 15.75c0-2.25 1.5-4.25 3.75-5.5ZM6 13.75h12");
}

.miscaab_g {
  d: path("M5.75 10.25c.5-2 3-3.25 6.25-3.25s5.75 1.25 6.25 3.25ZM12 7V4.75M4.75 12.5h-2m16.5 0h2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
