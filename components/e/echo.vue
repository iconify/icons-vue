<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm2qxbbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:echo" /></template>
<style>
.lm2qxbbmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.75H5L8 6.5v11l-3-3.25H2.5ZM21.5 3v18M11.005 8.995a4.25 4.25 0 0 1 0 6.01m6.201 1.495a9 9 0 0 1 0-9");
}

</style>
