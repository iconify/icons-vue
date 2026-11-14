<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nz6d2bo2f"/><path class="knhhmhqvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diplomatic-pouch" /></template>
<style>
.knhhmhqvz {
  d: path("M9.75 15.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.nz6d2bo2f {
  d: path("M2.5 9h19v12h-19ZM5 9c0-6.5 14-6.5 14 0M3.5 10l6.5 4m4 0l6.5-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
