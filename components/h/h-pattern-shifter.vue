<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giies-bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:h-pattern-shifter" /></template>
<style>
.giies-bho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 3V17m-6.5-4v8m13-8v8m-13-4h13");
}

</style>
