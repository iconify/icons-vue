<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogx2uab4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gizmo-scale" /></template>
<style>
.ogx2uab4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 14V6.5M9 14h8.5M9 14l-3.25 3.25M7.25 3h3.5v3.5h-3.5Zm10.25 9.25H21v3.5h-3.5Zm-15 5h3.25v3.25H2.5Z");
}

</style>
