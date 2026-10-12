<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy6-2bs7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bounding-box-sharp" /></template>
<style>
.oy6-2bs7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 4.5h11.5m1.75 1.75v11.5m-1.75 1.75H6.25M4.5 17.75V6.25m-1.75-3.5h3.5v3.5h-3.5zm15 0h3.5v3.5h-3.5zm0 15h3.5v3.5h-3.5zm-15 0h3.5v3.5h-3.5z");
}

</style>
