<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9m3tkber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-share-dock" /></template>
<style>
.t9m3tkber {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h5.5v18H3Zm7 12.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0ZM2.5 21h19m-13-5.5H10m5.5 0L18.25 4M15.5 15.5h.01");
}

</style>
