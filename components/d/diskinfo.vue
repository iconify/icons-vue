<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z5m96qnec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diskinfo" /></template>
<style>
.z5m96qnec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.881 28.972a21.48 21.48 0 0 1-15.928 15.93m-9.941 0A21.484 21.484 0 0 1 2.5 24c0-9.95 6.832-18.6 16.512-20.902m9.942 0a21.48 21.48 0 0 1 15.93 15.941");
}

</style>
