<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xi737t7bs"/><path class="beniqqiee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:combat-providence-analysis-system" /></template>
<style>
.beniqqiee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.125 28.625L24 14.75L33.25 24L24 33.25l4.625 4.625M24 24l-4.625 4.625");
}

.xi737t7bs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24L24 42.5L42.5 24L24 5.5z");
}

</style>
