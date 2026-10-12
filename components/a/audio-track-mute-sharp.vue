<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdsz7cctn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audio-track-mute-sharp" /></template>
<style>
.bdsz7cctn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6h18.5v12H2.75zm3.75 5v2m3-4v6m3-5v4m3-5v6m3-4v2");
}

</style>
