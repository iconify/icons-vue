<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdpr30akd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-buttons" /></template>
<style>
.tdpr30akd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm0 13a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm13 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
