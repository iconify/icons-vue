<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zzzz2bbvj"/><path class="pexua8b5e"/><circle class="dbx5zl31b"/><circle class="zz0fzgbrg"/><path class="yyemhnnic"/><path class="i7iysonby"/><path class="hukk54-ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lime3ds" /></template>
<style>
.dbx5zl31b {
  cx: 17.487px;
  cy: 27.792px;
  r: 1.625px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hukk54-ns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.21 9.435c3.555 0 3.17 1.662 3.17 1.662m.997-3.993c2.168 0 3.01.899 2.606 1.617m3.337 7.686l.573-2.976m-8.061 3.431l.239.494m12.826 1.833l2.032-2.249m1.491 8.237l2.952-.684m-3.572 7.82l2.79 1.181m-8.792 4.908l1.222 2.773m-11.342-3.148l-1.424 2.676m-4.322-9.881l-2.925.792m3.397-8.241l-2.801-1.155");
}

.i7iysonby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.556 6.078c-6.809.55-12.221 3.404-14.634 7.018");
}

.pexua8b5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.02 13.29a14.625 14.625 0 0 1 12.728 14.502c0 8.077-6.547 14.624-14.624 14.624S7.499 35.87 7.499 27.792c0-4.19 1.797-8.178 4.934-10.954");
}

.yyemhnnic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.81 30.387c-1.304 1.035-2.911 1.035-4.216 0m7.962-24.309c-8.723-2.584-17.772.794-18.36 10.54c5.799.33 15.244 2.32 17.277-9.457c.085-.464.519-.932 1.083-1.083");
}

.zz0fzgbrg {
  cx: 26.762px;
  cy: 27.792px;
  r: 1.625px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zzzz2bbvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.525 16.689a16.8 16.8 0 0 0-3.317 10.02C7.208 35.981 14.726 43.5 24 43.5s16.792-7.518 16.792-16.792A16.79 16.79 0 0 0 30.026 11.04a114 114 0 0 1 1.701-3.785A2.167 2.167 0 0 0 30.23 4.58c-.216-.06-.647-.08-.647-.08a2.17 2.17 0 0 0-2.025 1.578a238 238 0 0 1-.605 4.105q-.598-.108-1.2-.172");
}

</style>
