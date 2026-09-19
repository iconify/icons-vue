<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lsvacdcrw"/><path class="xfriufe_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:identiconizer" /></template>
<style>
.lsvacdcrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.1 35.1h7.4v7.4h-7.4zm-29.6 0h7.4v7.4H5.5z");
}

.xfriufe_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 27.7V12.9h-7.4v7.4h-7.4v-7.4h7.4V5.5H12.9v7.4h7.4v7.4h-7.4v-7.4H5.5v14.8h7.4v7.4h7.4v7.4h7.4v-7.4h7.4v-7.4z");
}

</style>
