<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i4y31nb2g"/><path class="ugdkcpnec"/><path class="uqx4bcc9c"/><ellipse class="vbtt1_b3p"/><path class="q0ns7_x7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dance-community" /></template>
<style>
.i4y31nb2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.449 27.03s-1.26-3.6.18-8.46m3.481 13.86s3.72 2.881 8.22 2.521");
}

.q0ns7_x7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.97 13.049s5.46-.12 8.4 3.18m3.061 13.141s1.68-4.26.18-8.64");
}

.ugdkcpnec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.247 13.75L24 3.5l17.754 10.25v20.5L24 44.5L6.247 34.25z");
}

.uqx4bcc9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.875 27.353c1.264-.45 2.81.358 3.453 1.804s.139 2.982-1.125 3.432s-2.81-.36-3.453-1.805s-.139-2.982 1.125-3.431");
}

.vbtt1_b3p {
  cx: 34.051px;
  cy: 18.089px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.371px;
  ry: 2.431px;
}

</style>
