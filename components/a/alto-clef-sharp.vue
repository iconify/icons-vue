<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0aazjb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alto-clef-sharp" /></template>
<style>
.j0aazjb7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h3v18.5h-3zm6 0v18.5m2.25-17l1.421-1.5h1.829c1.8 0 3 1.6 3 3.75c0 2.5-1.6 4-3.6 4h-1.567L13.25 9l-2.5 3l2.5 3l.833-1.5h1.567c2 0 3.6 1.5 3.6 4c0 2.15-1.2 3.75-3 3.75h-1.829L13 19.75");
}

</style>
