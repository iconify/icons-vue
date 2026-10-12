<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g794m7bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:air-freight-sharp" /></template>
<style>
.g794m7bgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.75 5h7.5v2.5h-7.5l-3 2.75h-2l1.5-2.75h-3.5L4.5 8.75H2.75l.5-2.5l-.5-2.5H4.5L5.75 5h3.5l-1.5-2.25h2ZM6.5 13h11v8.25h-11zm5.5 0v3");
}

</style>
