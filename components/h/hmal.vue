<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="hge0_7zrf"/><path class="dt-i-ebag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hmal" /></template>
<style>
.dt-i-ebag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.066 22.995h2.01v2.01h-2.01zm0-8.223h2.01v2.01h-2.01zm0 16.446h2.01v2.01h-2.01z");
}

.hge0_7zrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.807 5.5v37M15.438 29.608h12.37v5.23h-12.37a.77.77 0 0 1-.77-.77v-3.689a.77.77 0 0 1 .77-.77m0-8.224h12.37v5.23h-12.37a.77.77 0 0 1-.77-.77v-3.69a.77.77 0 0 1 .77-.77m0-8.223h12.37v5.23h-12.37a.77.77 0 0 1-.77-.771v-3.689a.77.77 0 0 1 .77-.77");
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

</style>
