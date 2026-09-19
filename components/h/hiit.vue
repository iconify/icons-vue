<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="bsgswrbce"/><path class="oskwt5bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hiit" /></template>
<style>
.bsgswrbce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.054 45.107a19.163 19.163 0 0 1-6.143-30.19m2.443-2.279A19.16 19.16 0 0 1 39.15 8.812");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oskwt5bby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.911 14.917l-1.923-1.91l-1.407 1.323l-1.923-1.969l5.404-4.948l1.816 1.93l-1.475 1.339l1.951 1.956m10.024-.648l4.33 16.106l-8.934 10.223m8.935-10.223l5.745 2.557");
}

</style>
