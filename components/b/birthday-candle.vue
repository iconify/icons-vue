<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-ohkocvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:birthday-candle" /></template>
<style>
.k-ohkocvz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9h5v12.5h-5Zm0 4.5l5-2m-5 6l5-2M12 6.25C10.6 5.4 10.5 3.9 12 2c1.5 1.9 1.4 3.4 0 4.25Z");
}

</style>
