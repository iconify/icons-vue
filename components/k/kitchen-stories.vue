<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gcq5-kbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kitchen-stories" /></template>
<style>
.gcq5-kbfe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.273 5.5c0 3.699-4.485 3.699-4.485 7.397c0 3.697 4.485 3.697 4.485 7.394c0 3.7-4.485 3.7-4.485 7.4c0 3.702 4.485 3.702 4.485 7.404S5.788 38.798 5.788 42.5m20.454-37c0 3.699-4.484 3.699-4.484 7.397c0 3.697 4.484 3.697 4.484 7.394c0 3.7-4.484 3.7-4.484 7.4c0 3.702 4.484 3.702 4.484 7.404s-4.484 3.703-4.484 7.405m20.454-37c0 3.699-4.485 3.699-4.485 7.397c0 3.697 4.485 3.697 4.485 7.394c0 3.7-4.485 3.7-4.485 7.4c0 3.702 4.485 3.702 4.485 7.404s-4.485 3.703-4.485 7.405");
}

</style>
