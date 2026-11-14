<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ukdudugbn"/><path class="nzqy8b1bz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:art-installation" /></template>
<style>
.nzqy8b1bz {
  d: path("M5.75 13.25L8 9.5L9.25 11");
}

.ukdudugbn {
  d: path("M3 5h9v11H3Zm12 0h6.5v8H15ZM2.5 19.5h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
