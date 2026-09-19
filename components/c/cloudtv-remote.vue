<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pi2rf6azi"/><path class="daop-fb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cloudtv-remote" /></template>
<style>
.daop-fb1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.127 24l-16.672-9.625v19.25z");
}

.pi2rf6azi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.343 39.062a21.5 21.5 0 1 1-.14-30.265");
}

</style>
