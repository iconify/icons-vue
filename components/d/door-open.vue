<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4mpo5bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:door-open" /></template>
<style>
.b4mpo5bvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 21.5V5a1.5 1.5 0 0 1 1.5-1.5h7A1.5 1.5 0 0 1 20 5v16.5M10 5L3.5 2.5v19L10 20Zm-3.75 7.5h.01");
}

</style>
