<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxnavbcck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:door-sensor" /></template>
<style>
.lxnavbcck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h8v16h-8Zm11 3h3a5 5 0 0 1 0 10h-3v-3h3a2 2 0 0 0 0-4h-3Zm-7 1h.01");
}

</style>
