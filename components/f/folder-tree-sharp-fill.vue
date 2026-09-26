<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="hbs5gpblk"/><path class="ibhxv1b9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-tree-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hbs5gpblk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 2L16 2C16.3788 2 16.725 2.214 16.8944 2.5528L17.618 4L21 4C21.5523 4 22 4.4477 22 5L22 10C22 10.5523 21.5523 11 21 11L13 11C12.4477 11 12 10.5523 12 10L12 3C12 2.4477 12.4477 2 13 2ZM13 13L16 13C16.3788 13 16.725 13.214 16.8944 13.5528L17.618 15L21 15C21.5523 15 22 15.4477 22 16L22 21C22 21.5523 21.5523 22 21 22L13 22C12.4477 22 12 21.5523 12 21L12 14C12 13.4477 12.4477 13 13 13Z");
  stroke: none;
}

.ibhxv1b9w {
  d: path("M3 2L3 19L10 19M3 5L3 8L10 8");
}

</style>
