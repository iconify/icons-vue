<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hya9bwksv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cable-tv" /></template>
<style>
.hya9bwksv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7h15v11h-15Zm4-4L10 7l3.5-4m4 9.5H19a1.5 1.5 0 0 1 1.5 1.5v4.5m-1.5 0h3v3h-3Z");
}

</style>
