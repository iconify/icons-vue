<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p11oomb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kuiper-belt" /></template>
<style>
.p11oomb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11.5 0h.01m-2.76 3.5h.01M12 17h.01m-6.76-1.5h.01M2.5 12h.01m2.74-3.5h.01M12 7h.01m6.74 1.5h.01");
}

</style>
