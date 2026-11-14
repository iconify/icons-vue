<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elt_fgf4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cleaning-gloves" /></template>
<style>
.elt_fgf4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 21.5l1-5.5v-2.5L2.75 11A1.25 1.25 0 0 1 4.5 9.25v-3a2.75 2.75 0 0 1 5.5 0V16l.5 5.5Zm17 0l-1-5.5v-2.5l1.75-2.5a1.25 1.25 0 0 0-1.75-1.75v-3a2.75 2.75 0 0 0-5.5 0V16l-.5 5.5ZM4.5 16H10m4 0h5.5");
}

</style>
