<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h3owedbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amazon-flex" /></template>
<style>
.h3owedbeo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 11.156L18.344 24L5.5 36.844M11.156 5.5L24 18.344L36.844 5.5M42.5 36.844L29.656 24L42.5 11.156M36.844 42.5L24 29.656L11.156 42.5");
}

</style>
