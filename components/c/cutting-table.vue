<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe-ctsbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cutting-table" /></template>
<style>
.fe-ctsbvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3.75-5.5L20 11M6.25 10L20 4.5m-17.5 17l3-6h16l-3 6Z");
}

</style>
