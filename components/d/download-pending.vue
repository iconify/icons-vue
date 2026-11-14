<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mdocvmbok"/><path class="lu0dhdb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:download-pending" /></template>
<style>
.lu0dhdb5q {
  d: path("M18 16.5V18l1 1");
}

.mdocvmbok {
  d: path("M4 15v3a2 2 0 0 0 2 2h6.25M12 3.5V15m-4.5-4.5L12 15l4.5-4.5M15 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
