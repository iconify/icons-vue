<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwfjiqb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gadget-repair" /></template>
<style>
.gwfjiqb9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12.6V2.5h7.2m4.8 11.3v7.7H8.2m9.55-17.25a3.5 3.5 0 0 0-4.5 4.5L5 17a1.5 1.5 0 0 0 2 2l8.25-8.25a3.5 3.5 0 0 0 4.5-4.5l-1.75 2L15.75 6Z");
}

</style>
