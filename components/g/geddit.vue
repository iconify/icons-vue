<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="l8pf2zpul"/><path class="ynk6r5ble"/><path class="ia1srnq-y"/><path class="yae6zxb0l"/><path class="jykjeybwe"/><ellipse class="reycs4b6t"/><ellipse class="rke6wbcwx"/><path class="o06zwzr4c"/><ellipse class="vrwfs9bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geddit" /></template>
<style>
.ia1srnq-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.45 20.16c3.38.96 5.65 3.66 6.55 6.58c-2.73 1.93-5.41 3.42-8.02 4.49M9.46 20.14c-2.38.46-5.99 3.62-6.46 6.62c2.04 1.77 4.97 3.14 7.91 4.49m-1.1 1.19c9.46 7.21 20.93 5.95 28.25-.05l-.05 4.11c-6.28 5.39-18.28 7.54-28.34.02z");
}

.jykjeybwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.55 20.96c-.43 1.6.61 2.81 1.27 4.12c-2.36-.95-5.03-1.26-6.41-4.3c.39 1.53-2.07 3.03-8.57 4.5c1.11-1.05 2.42-2.01 2.78-3.41m-3.3 1.16l1.54.96");
}

.l8pf2zpul {
  cx: 17.8px;
  cy: 27.6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.25px;
  ry: 1.95px;
}

.o06zwzr4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.96 13.98h3.85m-3.86 1.44h3.92m-5.59 15.17c-.07 5.93 8.1 4.43 6.95.02z");
}

.reycs4b6t {
  cx: 17.69px;
  cy: 14.66px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.33px;
  ry: 4.3px;
}

.rke6wbcwx {
  cx: 30.23px;
  cy: 14.54px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.45px;
  ry: 4.19px;
}

.vrwfs9bjj {
  cx: 29.91px;
  cy: 27.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.17px;
  ry: 1.84px;
}

.yae6zxb0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.45 37.23c-10.03-1.77-8.6-8.15-8.99-13.8c8.22-3.78 16.83-3.52 22.78-.07c.71 11.06-3.95 13.29-9.57 13.95");
}

.ynk6r5ble {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.42 35.3c4.25-2.42 5.14-7.72 5.03-15.14c-.11-7.41-5.91-13.52-14.65-13.55S10.09 13.67 9.47 20.13c-.62 6.47 1.09 13.16 4.91 15.08");
}

</style>
