<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ji81s9z9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ecoflow" /></template>
<style>
.ji81s9z9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 14.49h16.223M4.5 24h16.223M4.5 33.51h16.223m6.554-19.02H43.5M27.277 33.51V24H43.5");
}

</style>
