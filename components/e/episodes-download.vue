<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j82e4gbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:episodes-download" /></template>
<style>
.j82e4gbty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3L7 5L3.5 7Zm7 2h10m-17 5L7 12l-3.5 2v-4m7 2h4.7M3.5 17L7 19l-3.5 2v-4m7 2h1.6m5.9-4.5V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
