<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="imf3ivbka"/><circle class="fys-06bdg"/><ellipse class="pcy1uiskx"/><path class="jm8n840fv"/><path class="tej15xbjg"/><path class="tesbocbzu"/><circle class="fmra4nbeo"/><circle class="nyy6ltb4j"/><path class="tnco1ebxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ewesticker" /></template>
<style>
.fmra4nbeo {
  cx: 20.675px;
  cy: 13.671px;
  r: 0.75px;
  fill: currentColor;
}

.fys-06bdg {
  cx: 22.493px;
  cy: 13.71px;
  r: 4.391px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.imf3ivbka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.895 24.754a2.65 2.65 0 0 0 2.23 1.212l.052-.004a2.65 2.65 0 1 0 3.466 3.994a2.647 2.647 0 0 0 2.323 3.935a3.5 3.5 0 0 0 2.703-1.511v1.263a2.657 2.657 0 0 0 2.657 2.657a2.8 2.8 0 0 0 2.754-2.593a2.82 2.82 0 0 0 2.755 2.72a3.043 3.043 0 0 0 2.869-2.937a3.02 3.02 0 0 0 2.87 2.377a2.657 2.657 0 0 0 2.657-2.657a4.3 4.3 0 0 0-.804-2.246a3.16 3.16 0 0 0 2.762 1.854a2.657 2.657 0 0 0 1.451-4.881a2.657 2.657 0 0 0 .554-5.253a2.656 2.656 0 0 0-.351-5.29q-.107.003-.213.014a2.643 2.643 0 0 0-3.251-3.766q.008-.08.012-.16a2.65 2.65 0 0 0-4.17-2.177c-.026-1.449-1.702-2.61-3.15-2.61a2.883 2.883 0 0 0-2.809 2.763");
}

.jm8n840fv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.134 22.381a2.317 2.317 0 1 1-4.634 0m26.084 0a2.317 2.317 0 1 1-4.634 0m-1.53-.681a6.948 6.948 0 1 1-13.896 0m-6.024.681c.001-2.157 1.678-6.742 4.077-7.442m22.007 7.442a10.36 10.36 0 0 0-4.374-8.269m-.26 8.269c.127-3.935-.981-5.83-.982-5.815m-11.479-6.389a6.5 6.5 0 0 1 2.434-2.452a3.34 3.34 0 0 1 1.503-.37A4.27 4.27 0 0 1 21.98 9.26M11.524 21.7s-.184-3.702.312-4.964m4.813 23.818a31.2 31.2 0 0 1 2.766-6.915m.387 6.975a13.9 13.9 0 0 1 1.544-4.396m11.964 4.41a20 20 0 0 0-.68-4.884m3.862 4.901a18.6 18.6 0 0 0-.897-5.613M25.42 21.7s.116-3.543-.278-4.401");
}

.nyy6ltb4j {
  cx: 15.439px;
  cy: 13.71px;
  r: 0.75px;
  fill: currentColor;
}

.pcy1uiskx {
  cx: 13.614px;
  cy: 13.601px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.391px;
  ry: 3.404px;
}

.tej15xbjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.93 28.634s-1.763-.19-1.19-2.573");
}

.tesbocbzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.08 24.518s1.927 2.956 5.742.736m4.172-1.155c.023-.567-1.341-2.043-2.012-2.263");
}

.tnco1ebxn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.547 9.28s3.136-2.31 5.604.411m3.324-3.141s2.35-1.777 4.82 1.923M10.134 22.381s-.37-3.63 1.702-5.645");
}

</style>
