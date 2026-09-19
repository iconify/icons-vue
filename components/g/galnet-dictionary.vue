<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="y377dsleh"/><rect transform="matrix(-1 0 0 -1 31.745 50.07)" class="ueekm8gpi"/><path class="iziod8bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:galnet-dictionary" /></template>
<style>
.iziod8bfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.438 15.944v11.803c0 .931.755 1.686 1.687 1.686h.505m3.148 0l2.215-12.562m2.169 12.562l2.215-12.562m-7.739 8.937h7.925m-6.988-5.311H35.5");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ueekm8gpi {
  width: 6.745px;
  height: 8.937px;
  x: 12.5px;
  y: 20.567px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.372px;
  ry: 3.372px;
}

.y377dsleh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.245 20.567v10.117a3.37 3.37 0 0 1-3.373 3.372h0a3.36 3.36 0 0 1-2.384-.987");
}

</style>
