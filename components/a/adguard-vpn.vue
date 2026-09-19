<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="grj5w0bem"/><ellipse class="bgmuo_bmj"/><ellipse class="mv1jg9b6w"/><path class="mgn512ggo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adguard-vpn" /></template>
<style>
.bgmuo_bmj {
  cx: 17.83px;
  cy: 19.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.94px;
  ry: 2.13px;
}

.grj5w0bem {
  cx: 24px;
  cy: 18.6px;
  r: 14.1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mgn512ggo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.24c6.47 0 11.51 2 11.51 6.8c0 3.21-1.85 4.16-4.26 4.16c-2.13 0-4-1.25-7.25-1.25s-5.12 1.25-7.25 1.25c-2.41 0-4.26-.95-4.26-4.16c0-4.77 5.04-6.8 11.51-6.8M34.51 32c0 3.85-8.6 11.48-10.51 11.48S13.49 35.87 13.49 32");
}

.mv1jg9b6w {
  cx: 30.17px;
  cy: 19.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.94px;
  ry: 2.13px;
}

</style>
