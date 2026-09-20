<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x20k3rmnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:imgur" /></template>
<style>
.x20k3rmnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a5.58 5.58 0 0 1 5.58 5.58A5.58 5.58 0 0 1 24 15.66a5.58 5.58 0 0 1-5.58-5.58A5.58 5.58 0 0 1 24 4.5m0 15.13a5.79 5.79 0 0 1 5.58 6v11.86a5.79 5.79 0 0 1-5.58 6a5.79 5.79 0 0 1-5.58-6V25.64A5.79 5.79 0 0 1 24 19.63");
}

</style>
