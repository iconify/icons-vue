<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw0x38brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:girder-sharp" /></template>
<style>
.jw0x38brl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h18.5v2.5H2.75zm0 10h18.5v2.5H2.75zm1 0l3.75-7.5l4.5 7.5l4.5-7.5l3.75 7.5");
}

</style>
