<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_5p-wzmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-dairy-eggs" /></template>
<style>
.n_5p-wzmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 18.599V21.5H3v-12L5 3h4.5l2 6.5v8.899M3 9.5h8.5m6.25 3.5c2.5 0 3.5 3.5 3.5 5.5a3.5 3.5 0 0 1-7 0c0-2 1-5.5 3.5-5.5Z");
}

</style>
