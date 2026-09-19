<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lym4bor2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:curioshuffle" /></template>
<style>
.lym4bor2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 4.5A5.5 5.5 0 0 0 33 10v25.5a8 8 0 0 1-8 8H9.5A5.5 5.5 0 0 0 15 38V12.5a8 8 0 0 1 8-8z");
}

</style>
