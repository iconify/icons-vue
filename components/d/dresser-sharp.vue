<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfks4_bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dresser-sharp" /></template>
<style>
.jfks4_bno {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3.75h11.5v8.5H6.25zm-3.5 8.5h18.5v7H2.75zm0 3.5h18.5m-12.33-3.5v3.5m6.16-3.5v3.5m-9.83 3.5v2m13.5-2v2");
}

</style>
