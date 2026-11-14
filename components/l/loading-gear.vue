<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vmt7z_2gl"/><path class="u3f7hpblx"/><path class="a3xey_y6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loading-gear" /></template>
<style>
.a3xey_y6d {
  d: path("M20.75 4.75L20 7.5l-2.75-.75m-14 12.5L4 16.5l2.75.75");
}

.u3f7hpblx {
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM3.989 7.375a9.25 9.25 0 0 1 16.022 0m0 9.25a9.25 9.25 0 0 1-16.022 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vmt7z_2gl {
  d: path("m11 7.356l.168-1.55h1.664L13 7.356l1.577.654l1.215-.978l1.176 1.176l-.978 1.215l.654 1.577l1.55.168v1.664l-1.55.168l-.654 1.577l.978 1.215l-1.176 1.176l-1.215-.978l-1.577.654l-.168 1.55h-1.664L11 16.644l-1.577-.654l-1.215.978l-1.176-1.176l.978-1.215L7.356 13l-1.55-.168v-1.664L7.356 11l.654-1.577l-.978-1.215l1.176-1.176l1.215.978Z");
}

</style>
