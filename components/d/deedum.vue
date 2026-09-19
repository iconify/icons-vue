<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q4r95ccqq"/><path class="bdo7nm0hx"/><path class="ulau59bpz"/><path class="psyf6_b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:deedum" /></template>
<style>
.bdo7nm0hx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.483 4.5v7.465h3.805v20.911h-3.805v7.465H8.697V4.5Z");
}

.psyf6_b8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.657 12.039h11.064v20.762H16.657z");
}

.q4r95ccqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.803 7.66h2.695v4.552m.88 2.912h2.925v20.911h-3.805V43.5H11.712v-2.85");
}

.ulau59bpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.672 15.644v17.157h8.048V15.644Z");
}

</style>
