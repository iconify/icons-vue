<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls_nabb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-pipe-yellow" /></template>
<style>
.ls_nabb7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H5v9.5H2.5ZM19 12h2.5v9.5H19ZM5 13.75h14m-14 6h14M12 2.5c1.5 2 3.25 3.25 3.25 5.25a3.25 3.25 0 0 1-6.5 0c0-1.25.75-2.25 1.5-2.75c.25 1 .75 1.5 1.25 1.75c-.25-1.5 0-3 .5-4.25Z");
}

</style>
