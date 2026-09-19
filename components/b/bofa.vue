<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c3def_g_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bofa" /></template>
<style>
.c3def_g_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.541 31.494L36.98 20.271M24.061 35.258L43.5 24.035m-39-.07l6.48-3.741m.04 7.505l6.48-3.741m6.439-11.246l6.52 3.764m-13-.023l6.521 3.764");
}

</style>
