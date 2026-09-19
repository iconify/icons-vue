<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ycx-h1bwj"/><circle class="us4708y-t"/><path class="ber_12b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ebird" /></template>
<style>
.ber_12b3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.132 27.848a2.54 2.54 0 0 1-2.21 1.299c-1.404 0-2.543-1.152-2.543-2.574v-1.672c0-1.422 1.139-2.574 2.543-2.574s2.543 1.152 2.543 2.574v.836H9.38m29.24-.837c0-1.421-1.138-2.573-2.543-2.573s-2.543 1.152-2.543 2.573v1.673c0 1.421 1.139 2.573 2.543 2.573s2.543-1.152 2.543-2.573m0 2.574V18.853M21.108 24c1.405 0 2.543 1.152 2.543 2.573s-1.139 2.574-2.543 2.574h-4.196V18.853h4.196c1.404 0 2.543 1.152 2.543 2.573S22.512 24 21.108 24m0 0h-4.191m9.181-1.673v6.82");
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

.us4708y-t {
  cx: 26.098px;
  cy: 19.175px;
  r: 0.75px;
  fill: currentColor;
}

.ycx-h1bwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.545 24.9c0-1.421 1.139-2.573 2.543-2.573m-2.543 0v6.82");
}

</style>
