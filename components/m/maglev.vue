<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9ywk5b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:maglev" /></template>
<style>
.f9ywk5b3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14.5V6a2 2 0 0 1 2-2h9c4 0 7 4 7 8v2.5ZM2.5 20h19M6 17.25h3m6 0h3M3 8.5h14.5");
}

</style>
