<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4t89nakp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:key-finder" /></template>
<style>
.d4t89nakp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm10.25-4.75a7.5 7.5 0 0 1 0 9.5m-11.5 0a7.5 7.5 0 0 1 0-9.5M12 12.5v9m0-4h2.5m-2.5 3h3");
}

</style>
