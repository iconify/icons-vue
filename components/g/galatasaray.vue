<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ypaatojaj"/><path class="mysnmch-s"/><ellipse class="hbx39q6of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:galatasaray" /></template>
<style>
.hbx39q6of {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.054px;
  ry: 21px;
}

.mysnmch-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.83 20.628A11.13 11.13 0 0 0 24 17.412c-6.13 0-11.1 4.945-11.1 11.044S17.87 39.5 24 39.5s11.1-4.945 11.1-11.044l-5.75.05");
}

.ypaatojaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.536 28.35a8.46 8.46 0 0 0 16.92 0c.138-10.48-13.556-5.472-14.317-14.038c.002-3.21 2.629-5.812 5.866-5.812s5.859 2.602 5.856 5.812");
}

</style>
