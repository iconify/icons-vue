<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6ynmpcsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:contour-integral-sharp" /></template>
<style>
.g6ynmpcsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17 4.5l-.833-1.25H14.75c-1.75 0-2.75 1.25-3 3l-1.5 11.5c-.25 1.75-1.25 3-3 3H5.833L5 19.5");
}

</style>
