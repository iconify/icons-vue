<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oxjx7cb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:datawing" /></template>
<style>
.oxjx7cb1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5L15.5 30l8.87-2.81l8.13 2.79Zm-4.9 24.32V43.5m3.23-15.71V43.5m3.86-15.73V43.5M29.63 29v14.5");
}

</style>
