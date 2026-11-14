<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9miqfj3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lowercase" /></template>
<style>
.b9miqfj3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm7-4V19m3-14v14m0-3.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

</style>
