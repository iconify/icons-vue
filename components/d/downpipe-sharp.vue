<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhjiw6b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:downpipe-sharp" /></template>
<style>
.mhjiw6b1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.75h2.75v15.5l-.53.53l-1.94 1.94l-.53.53h-6v-3.5H10v-15zm8 0v18.5M13.5 7h5.25m-5.25 6h5.25M10 7h3.5M10 13h3.5");
}

</style>
