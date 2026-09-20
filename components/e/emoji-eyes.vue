<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vwqzhob_r"/><path class="o6p5p2b-q"/><path class="ny0js1c4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-eyes" /></template>
<style>
.ny0js1c4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 25.112a4.8 4.8 0 0 0 4.8 4.802a4.8 4.8 0 0 0 4.805-4.797v-.006c.002-2.65-2.148-4.8-4.8-4.801S5.501 22.456 5.5 25.107zm19.687 0a4.8 4.8 0 0 0 4.802 4.799a4.801 4.801 0 1 0 .002-9.601a4.8 4.8 0 0 0-4.805 4.797z");
}

.o6p5p2b-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.135 25.112a2.167 2.167 0 0 0 4.335 0a2.167 2.167 0 0 0-4.335 0m19.687 0a2.167 2.167 0 0 0 4.335 0a2.167 2.167 0 0 0-4.335-.004z");
}

.vwqzhob_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24c0 8.141 3.876 14.74 8.657 14.74s8.657-6.599 8.657-14.74s-3.876-14.74-8.657-14.74S5.5 15.858 5.5 24m19.687 0c-.001 8.141 3.874 14.742 8.655 14.743s8.657-6.598 8.658-14.739V24c0-8.141-3.874-14.742-8.655-14.743c-4.782-.001-8.658 6.598-8.659 14.739z");
}

</style>
