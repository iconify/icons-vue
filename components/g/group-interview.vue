<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykffefblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:group-interview" /></template>
<style>
.ykffefblm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h8A1.5 1.5 0 0 1 17.5 4v3A1.5 1.5 0 0 1 16 8.5h-2.75L12 9.75L10.75 8.5H8A1.5 1.5 0 0 1 6.5 7V4A1.5 1.5 0 0 1 8 2.5ZM2.5 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2 21.5c0-1.75 1-2.75 2.5-2.75s2.5 1 2.5 2.75m2.5 0c0-1.75 1-2.75 2.5-2.75s2.5 1 2.5 2.75m2.5 0c0-1.75 1-2.75 2.5-2.75s2.5 1 2.5 2.75");
}

</style>
