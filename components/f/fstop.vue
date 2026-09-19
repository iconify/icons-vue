<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="x18rz_cgq"/><circle class="eo28r3diu"/><path class="hw3gyut4l"/><circle class="cpk0fnbgt"/><path class="iqymt4bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fstop" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eo28r3diu {
  cx: 21.429px;
  cy: 17.668px;
  r: 2.369px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hw3gyut4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.162 26.176l4.197-3.833l4.257 3.712l.3.312l6.86-6.486l6.072 6.071m-13.028.461l-5.89 5.462");
}

.iqymt4bay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.976 35.108l2.589 9.659m-8.541-31.875l-2.589-9.659m16.673 23.743l9.659 2.589m-31.875-8.541l-9.659-2.589m28.899-2.567l7.071-7.071M15.868 32.132l-7.071 7.071");
}

.x18rz_cgq {
  cx: 24px;
  cy: 24px;
  r: 11.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
