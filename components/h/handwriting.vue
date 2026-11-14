<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f050x57gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:handwriting" /></template>
<style>
.f050x57gx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5C6 20.5 6.5 14 9 14s1.5 5 4 5c2 0 2.5-3 4-3.5c1-.25 2 .5 3.5.5M16 3.5L20.5 8L13 12.5l-2.5.5l.5-2.5Z");
}

</style>
