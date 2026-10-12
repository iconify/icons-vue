<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er4m7db0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lip-gloss-sharp" /></template>
<style>
.er4m7db0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 9.25h5.5v12h-5.5zM7 12.5v5m9.75-7l-.63-5.84a2.4 2.4 0 1 1 4.56 1.48Zm-.15.5l-1.4 4.4m-.78.66l.96.3l.95.31l-.31.95l-.76 2.38l-.31.95l-.95-.31l-.96-.3l-.95-.31l.31-.95l.76-2.38l.31-.95z");
}

</style>
