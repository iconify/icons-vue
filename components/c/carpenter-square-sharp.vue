<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h94b_2xsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carpenter-square-sharp" /></template>
<style>
.h94b_2xsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h4v14.5h-4zm0 14.5h18.5v4H2.75zm7.25 0V19m3.5-1.75V19m3.5-1.75V19");
}

</style>
