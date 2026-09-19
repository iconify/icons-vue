<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eckhj5bmo"/><path class="c8frlpb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ichaival" /></template>
<style>
.c8frlpb7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 35.85V15.589h-1.842L24 11.905l1.842 3.684H24");
}

.eckhj5bmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 36.095a19.8 19.8 0 0 1 39 0Z");
}

</style>
