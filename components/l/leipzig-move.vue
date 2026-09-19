<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k4qn-xlco"/><rect transform="rotate(145.904 16.898 22.973)" class="qzigt16nn"/><path class="b6q7b1w5l"/><path class="uo4bp1bzh"/><path class="dlvgq2ond"/><path class="psnum4b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:leipzig-move" /></template>
<style>
.b6q7b1w5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.47 11.543a4.943 4.943 0 0 0-6.969 1.485l-8.267 13.309a4.33 4.33 0 0 0 1.25 5.868h0a4.33 4.33 0 0 0 5.912-1.02l9.285-12.62a4.943 4.943 0 0 0-1.21-7.022Z");
}

.dlvgq2ond {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 27.325c0 3.254-5.892 10.051-5.892 10.051s-5.891-6.797-5.891-10.05a5.892 5.892 0 0 1 11.783 0");
}

.k4qn-xlco {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.312 13.742a4.163 4.163 0 0 1 1.113 5.779l-4.32 6.383a4.163 4.163 0 0 1-5.78 1.113h0a4.163 4.163 0 0 1-1.113-5.78l4.32-6.382a4.163 4.163 0 0 1 5.78-1.113");
}

.psnum4b2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.633 30.417h-1.688c-.91 0-1.648-.737-1.648-1.647v-4.53");
}

.qzigt16nn {
  width: 8.323px;
  height: 22.296px;
  x: 12.736px;
  y: 11.825px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.162px;
  ry: 4.162px;
}

.uo4bp1bzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.313 31.493l-7.93-12.701a5.346 5.346 0 0 1 1.544-7.249h0a5.346 5.346 0 0 1 7.303 1.26l8.125 11.042");
}

</style>
