<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="up6rybbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hyvee" /></template>
<style>
.up6rybbgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.163 4.5v31.2c0 5.426 4.821 7.22 9.75 7.8V16.875h5.85V43.5c5.106-.284 10.075-1.953 10.075-7.8V4.5H26.762v8.775h-5.85V4.5Z");
}

</style>
