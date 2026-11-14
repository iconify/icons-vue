<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in7ad74oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cause-cancer-research" /></template>
<style>
.in7ad74oz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.665 21H3.5l6-12.5v-6h5v6l.606 1.262M14.75 21.75l4.75-5.5a2.5 2.5 0 1 0-3 0l4.75 5.5");
}

</style>
