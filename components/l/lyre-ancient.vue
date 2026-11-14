<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo5pos9uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lyre-ancient" /></template>
<style>
.oo5pos9uo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15C3.5 11 3.5 6 6 3m11 12c3.5-4 3.5-9 1-12M4.75 5h14.5M5.5 15h13v2a4 4 0 0 1-4 4h-5a4 4 0 0 1-4-4ZM9.25 5v10M12 5v10m2.75-10v10");
}

</style>
