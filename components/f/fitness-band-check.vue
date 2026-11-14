<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cgg7rjy0i"/><path class="c09svp7_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fitness-band-check" /></template>
<style>
.c09svp7_z {
  d: path("m10.25 12l1.25 1.25l2.25-2.75");
}

.cgg7rjy0i {
  d: path("M10 5.5h4A1.5 1.5 0 0 1 15.5 7v10a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 17V7A1.5 1.5 0 0 1 10 5.5Zm0 0v-3h4v3m-4 13v3h4v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
