<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_tu9-mfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cross-latin-sharp" /></template>
<style>
.s_tu9-mfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.75H14V5.5h5v4h-5v5.75h-4V9.5H5v-4h5V2.75zM6.5 18.25h11v3h-11z");
}

</style>
