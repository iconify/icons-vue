<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x5s47feon"/><rect class="mi4ibbc8w"/><circle class="irm9u67wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:finddevice" /></template>
<style>
.irm9u67wy {
  cx: 24px;
  cy: 32.23px;
  r: 0.75px;
  fill: currentColor;
}

.mi4ibbc8w {
  width: 14.94px;
  height: 24.99px;
  x: 16.53px;
  y: 9.32px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.79px;
}

.x5s47feon {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.29 4.5h-1.26a16.71 16.71 0 0 0-14.4 9.21a16.33 16.33 0 0 0-2 8.21a16.9 16.9 0 0 0 4.75 12.11c1.8 1.92 2.35 2.3 7.15 5a20 20 0 0 1 3.94 2.89L24 43.5l1.81-1.69a23.5 23.5 0 0 1 4.06-2.93c1.25-.67 3.15-1.84 4.22-2.59a17.69 17.69 0 0 0 5.49-22.16a17.4 17.4 0 0 0-8.16-8a14.75 14.75 0 0 0-7.13-1.63m-7.76 9h14.94M16.53 30.13h14.94");
}

</style>
