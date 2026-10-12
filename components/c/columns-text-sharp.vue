<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq_wby43g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:columns-text-sharp" /></template>
<style>
.gq_wby43g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75h7m-7 4.75h7m-7 4.75h7m-7 4.75h7m2.5-14.25h7m-7 4.75h7m-7 4.75h7m-7 4.75h4.5");
}

</style>
