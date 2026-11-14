<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jad_ajbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keep-refrigerated" /></template>
<style>
.jad_ajbkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.4 21.5H4v-19h13v10.2M4 11h13M6.75 5.25v3m0 5.5v4.75m11.75-3v6M15.75 17l5.5 3m-5.5 0l5.5-3");
}

</style>
