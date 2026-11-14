<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiv_i8xqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discount-percent" /></template>
<style>
.xiv_i8xqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5a9.5 9.5 0 0 1 4.015.89m2.703 1.892a9.5 9.5 0 0 1 2.209 3.469M21.5 12a9.5 9.5 0 0 1-.89 4.015m-1.892 2.703a9.5 9.5 0 0 1-3.469 2.209M12 21.5a9.5 9.5 0 0 1-4.015-.89m-2.703-1.892a9.5 9.5 0 0 1-2.209-3.469M2.5 12a9.5 9.5 0 0 1 .89-4.015m1.892-2.703a9.5 9.5 0 0 1 3.469-2.209M8.5 15.5l7-7m-8.25.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.5 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
