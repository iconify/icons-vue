<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n3izh9rmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fortuno" /></template>
<style>
.n3izh9rmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24c0 10.217-8.283 18.5-18.5 18.5S5.5 34.217 5.5 24S13.783 5.5 24 5.5h18.5z");
}

</style>
