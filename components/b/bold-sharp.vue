<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw-mb1bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bold-sharp" /></template>
<style>
.cw-mb1bmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3.75h6.5a4 4 0 0 1 0 8h-6.5Zm0 8h7.5a4.25 4.25 0 0 1 0 8.5h-7.5Z");
}

</style>
