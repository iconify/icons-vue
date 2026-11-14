<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rydli66-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-fingers" /></template>
<style>
.rydli66-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.371 6.379l3.668-.78l3.119 14.673l-3.668.779Zm6.358-1.351l3.668-.78l3.119 14.672l-3.668.78Zm6.358-1.352l3.668-.779l3.119 14.672l-3.668.78Z");
}

</style>
