<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="df39e3qck"/><circle class="ceu-4923b"/><path class="vzz5c1b3k"/><path class="jc-01rbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:izome-parent" /></template>
<style>
.ceu-4923b {
  cx: 10.5px;
  cy: 10.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.df39e3qck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.57 32.5H37.5a5 5 0 0 1 0 10H20.618");
}

.jc-01rbid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.74 11.191a3.333 3.333 0 0 0-2.358-5.69H37.5a5 5 0 0 1 3.536 8.535L18.26 36.81a3.333 3.333 0 0 0 2.357 5.69H10.5a5 5 0 0 1-3.536-8.535z");
}

.vzz5c1b3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 10.5V24a5 5 0 0 1-10 0v-1.429M5.5 37.5V24a5 5 0 0 1 10 0v1.43m9.93-9.929H24a5 5 0 0 1 0-10h3.383");
}

</style>
