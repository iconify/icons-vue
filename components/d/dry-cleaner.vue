<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo_jb-w3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dry-cleaner" /></template>
<style>
.yo_jb-w3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5h17l-2 11h-13Zm3 0c0-4.5 4-5.5 6-3.5c2-1.5 5.5-.5 5 3.5m-8.75 3v5m3.25-5v5m3.25-5v5");
}

</style>
