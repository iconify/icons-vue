<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c59hirbvx"/><path class="z8ujw6d6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ifruit" /></template>
<style>
.c59hirbvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24.082a18.5 18.5 0 0 0 37 0Zm20.063 0a8.381 8.381 0 0 0-16.762 0");
}

.z8ujw6d6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.2 24.082a8.382 8.382 0 0 0-15.207-4.866m-7.908-3.442c.63-4.775 12.333-13.82 21.02-8.966v2.045s-9.547.815-14.418 8.91");
}

</style>
