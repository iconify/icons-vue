<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_p6d0y6q"/><path class="uksgo5btf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:helmet-tear-off" /></template>
<style>
.o_p6d0y6q {
  d: path("M2.5 14c0-6 4-10 9-10C16 4 19 7.5 19 12v5.5a2 2 0 0 1-2 2H4.5a2 2 0 0 1-2-2Z");
}

.uksgo5btf {
  d: path("M19 9.75h-8a2.25 2.25 0 0 0 0 4.5h8m0-4.5c2 0 3 1.75 2 4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
