<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgo_dwgkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fabric-glue" /></template>
<style>
.wgo_dwgkw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.25 6.5l1-3.5h1l1 3.5m-4.5 0h6V9h-6Zm6.4 15h-8.9V9h11v3.2m.25 2.8h6v5q-1.5 2-3 0q-1.5 2-3 0Z");
}

</style>
