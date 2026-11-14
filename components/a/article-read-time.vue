<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjlnwzb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:article-read-time" /></template>
<style>
.cjlnwzb0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.9 20H2.5V2.5h11v6.6M6 7h4m-4 4h2.5m3.25 5.25a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

</style>
