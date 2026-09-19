<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mec7r5b3u"/><ellipse class="oifh4pw4g"/><ellipse class="jb20bkeja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cowsay" /></template>
<style>
.jb20bkeja {
  cx: 28.762px;
  cy: 22.93px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.585px;
  ry: 3.073px;
}

.mec7r5b3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.087 29.92a10.55 10.55 0 0 0-2.435 6.181a10.55 10.55 0 0 0 2.435 6.181M34.913 29.92a10.55 10.55 0 0 1 2.435 6.181a10.55 10.55 0 0 1-2.435 6.181M14.897 43.5h18.234m1.782-15.93a10.55 10.55 0 0 0 2.435-6.18a10.55 10.55 0 0 0-2.435-6.18M13.087 27.57a10.55 10.55 0 0 1-2.435-6.18a10.55 10.55 0 0 1 2.435-6.18m20.016-1.218H14.869m25.664-5.847L37.305 4.5l-3.227 3.645m-20.156 0L10.695 4.5L7.467 8.145");
}

.oifh4pw4g {
  cx: 19.238px;
  cy: 22.93px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.585px;
  ry: 3.073px;
}

</style>
