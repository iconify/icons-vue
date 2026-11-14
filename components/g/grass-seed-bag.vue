<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c9a6f4_3u"/><path class="naqrvfbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grass-seed-bag" /></template>
<style>
.c9a6f4_3u {
  d: path("m6.5 6.5l-.5-4l3 1.75l3-1.75l3 1.75l3-1.75l-.5 4C20 11 20 17 19 21.5H5C4 17 4 11 6.5 6.5Zm0 0h11M12 18v-4.5");
}

.naqrvfbyp {
  d: path("M12 14.5c0-2 2-3 3.5-3c0 2-2 3-3.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
