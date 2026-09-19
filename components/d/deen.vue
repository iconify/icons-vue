<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="elv5sybdv"/><path class="es0a1-b8p"/><path class="k_-meb-oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:deen" /></template>
<style>
.elv5sybdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.25 18.833l2.583 2.584L16.25 24l-2.583-2.583z");
}

.es0a1-b8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.167 16.25l-2.583 2.583l-7.75-7.75l-2.584 2.584l7.75 7.75l-7.75 7.75l-7.75-7.75L5.917 24L16.25 34.333l15.5-15.5zm-7.75 18.083L24 36.916L21.417 39.5l-2.583-2.583zm5.166-5.166l2.583 2.583l-2.583 2.584L24 31.75z");
}

.k_-meb-oz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.75 8.5l-2.583 2.583l7.75 7.75l-7.75 7.75l2.583 2.584l10.333-10.333L39.5 16.25z");
}

</style>
