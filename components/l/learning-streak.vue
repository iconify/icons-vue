<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmbdclcsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:learning-streak" /></template>
<style>
.rmbdclcsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3s6 5.5 6 11a6 6 0 0 1-12 0c0-2.75 1.75-4.5 3-6c0 1.75.75 3 2 3c-.5-2.75 0-5.5 1-8ZM9.5 21.5h5");
}

</style>
