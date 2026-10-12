<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2u5uenyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barbell-sharp" /></template>
<style>
.c2u5uenyi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8.5h2v7h-2zm2-2.5h2.25v12H5.5zm10.75 0h2.25v12h-2.25zm2.25 2.5h2v7h-2zM2.75 12h.75m4.25 0h8.5m4.25 0h.75");
}

</style>
