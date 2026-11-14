<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rikq9p_pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:censer-swinging" /></template>
<style>
.rikq9p_pp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13h14a7 7 0 0 1-14 0ZM6.5 3h7m-7 0L5 13m8.5-10L15 13M10 3v10m9.5-1.5c-1.5-2 1.5-3.5 0-6");
}

</style>
