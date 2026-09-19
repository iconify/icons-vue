<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dbi0u3iwj"/><circle class="lf289rbtz"/><circle class="icm9hty_n"/><path class="way3ajbzs"/><circle class="q2bfxm5nr"/><circle class="w8yktgeuw"/><path class="r3nfl8bwr"/><path class="p8t0m6bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iconic" /></template>
<style>
.dbi0u3iwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.139 22.246C15.84 9.692 36.076 9.8 36.076 24.096S15.84 38.503 19.14 25.949");
}

.icm9hty_n {
  cx: 29.198px;
  cy: 18.919px;
  r: 1.422px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lf289rbtz {
  cx: 23.618px;
  cy: 17.692px;
  r: 1.422px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p8t0m6bld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.043 11.057L7.827 24m32.346 0l2.784-12.943c.342-1.618-1.202-3.011-2.784-3.259H7.828C6.245 8.046 4.7 9.44 5.043 11.057m0 25.887L7.827 24m32.346 0l2.784 12.944c.342 1.616-1.202 3.01-2.784 3.258H7.828c-1.583-.248-3.127-1.642-2.785-3.258");
}

.q2bfxm5nr {
  cx: 23.618px;
  cy: 30.494px;
  r: 1.422px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r3nfl8bwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.471 25.4v-2.577c-7.536-1.208-14.446.38-14.446 1.289s6.91 2.497 14.446 1.289m-2.736-2.903v3.228m2.736-.326c1.815 1.619 3.427-.332 5.643-.698c-1.669-1.39-3.539-3.487-5.643-1.879M11.129 4.5a3.295 3.295 0 0 0-3.302 3.298h32.345A3.295 3.295 0 0 0 36.87 4.5ZM7.827 40.202a3.295 3.295 0 0 0 3.302 3.298H36.87a3.295 3.295 0 0 0 3.302-3.298Z");
}

.w8yktgeuw {
  cx: 29.198px;
  cy: 29.268px;
  r: 1.422px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.way3ajbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.644 22.672a1.42 1.42 0 0 0-1.411 1.272c.3.259.594.518.882.757a5 5 0 0 0-.669.16a1.422 1.422 0 1 0 1.198-2.19");
}

</style>
