<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="irnzejbzp"/><path class="zuw_o9_eu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-zoom-out" /></template>
<style>
.irnzejbzp {
  d: path("M3.5 12.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm10.25 4.25L18 21M16.5 5.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zuw_o9_eu {
  d: path("m6.5 14.5l2-3l2 1.5l2-3");
}

</style>
