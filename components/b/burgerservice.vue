<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nvchwbarr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:burgerservice" /></template>
<style>
.nvchwbarr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.292 15.761V43.5M22.15 29.63a6.935 6.935 0 0 1 0 13.87H10.708V15.761H22.15a6.935 6.935 0 1 1 0 13.87m0 0H10.708m0-19.486h26.584M10.708 4.5v5.645M37.292 4.5v5.645M24 4.5v5.645");
}

</style>
