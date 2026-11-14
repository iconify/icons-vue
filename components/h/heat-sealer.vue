<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swix0sbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-sealer" /></template>
<style>
.swix0sbfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h18v4H3Zm2.5 4l-1 12.5A1.5 1.5 0 0 0 6 21h12a1.5 1.5 0 0 0 1.5-1.5L18.5 7m-10-4v4M12 3v4m3.5-4v4");
}

</style>
