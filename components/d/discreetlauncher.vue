<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s6tqidb5b"/><path class="s3ldh7bto"/><path class="mlsn1e1nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:discreetlauncher" /></template>
<style>
.mlsn1e1nj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.73 30.37V43.5h20.54V30.37");
}

.s3ldh7bto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.13 30.54L24 12.79L6.87 30.54");
}

.s6tqidb5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.13 22.25L24 4.5L6.87 22.25");
}

</style>
