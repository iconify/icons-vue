<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urx34_qmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eggs-clutch" /></template>
<style>
.urx34_qmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h18c-.5 5-4.5 7.5-9 7.5S3.5 17 3 12Zm1.75 0c0-3.5.75-5.5 1.5-5.5s1.5 2 1.5 5.5m2.75 0c0-4.5.75-7.5 1.5-7.5s1.5 3 1.5 7.5m2.75 0c0-3.5.75-5.5 1.5-5.5s1.5 2 1.5 5.5");
}

</style>
