<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e0jp_eb_r"/><path class="b13sl2bwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ir-blaster" /></template>
<style>
.b13sl2bwi {
  d: path("M10.75 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM9.5 6.5a3.5 3.5 0 0 1 5 0M7.25 4.25a6.75 6.75 0 0 1 9.5 0");
}

.e0jp_eb_r {
  d: path("M8 9.5h8v12H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
