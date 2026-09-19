<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jsees_b1e"/><circle class="ulncyrb2w"/><path class="mp7kf5lqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:camcov" /></template>
<style>
.jsees_b1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.286 43.5H14.714a2.457 2.457 0 0 1-2.457-2.457V6.957c0-1.357 1.1-2.457 2.457-2.457h18.572c1.357 0 2.457 1.1 2.457 2.457v34.085c0 1.358-1.1 2.458-2.457 2.458m2.454-5.772H12.26m23.48-27.456H12.26");
}

.mp7kf5lqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.921 21.783h-9.064m2.239 4.434h-9.017m9.961-10.185l-4.54 7.864m4.963.273l-4.503 7.799m-3.84-13.719l4.43 7.674m2.826-3.974l4.505 7.802");
}

.ulncyrb2w {
  cx: 24px;
  cy: 24px;
  r: 8.223px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
