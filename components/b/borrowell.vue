<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zgpuwd7fk"/><path class="eel3j_bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:borrowell" /></template>
<style>
.eel3j_bgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.433 30.067C37.433 37.486 31.419 43.5 24 43.5H10.567V30.067c0-7.419 6.014-13.433 13.433-13.433s13.433 6.014 13.433 13.433");
}

.zgpuwd7fk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.433 17.933c0 7.419-6.014 13.433-13.433 13.433s-13.433-6.014-13.433-13.433V4.5H24c7.419 0 13.433 6.014 13.433 13.433");
}

</style>
