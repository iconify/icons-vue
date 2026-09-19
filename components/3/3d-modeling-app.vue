<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m2iza61ye"/><path class="i29mtbbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:3d-modeling-app" /></template>
<style>
.i29mtbbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.072 15.916l19.861 11.467l19.995-11.938M23.935 27.382l.159 16.816");
}

.m2iza61ye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.072 15.916l5.301 19.786l14.72 8.498l14.35-8.285l5.485-20.47L23.758 3.8z");
}

</style>
