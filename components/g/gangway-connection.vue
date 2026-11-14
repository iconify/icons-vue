<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpsn3lbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gangway-connection" /></template>
<style>
.tpsn3lbvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h6v14h-6Zm13 0h6v14h-6Zm-7 3l1.75-1.5L12 8l1.75-1.5L15.5 8m-7 8l1.75 1.5L12 16l1.75 1.5L15.5 16");
}

</style>
