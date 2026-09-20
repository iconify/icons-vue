<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="oxpd-u55x"/><path class="u2w1ocqzb"/><path class="wtq_tlbqq"/><circle class="alwqyvbkb"/><path class="nr87ilqat"/><circle class="q904vmstc"/><circle class="t_s3j0b-f"/><path class="vei_7lg5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:eye" /></template>
<style>
.alwqyvbkb {
  cx: 64.32px;
  cy: 60.79px;
  r: 33.15px;
  fill: var(--svg-color--9c7a63, #9c7a63);
}

.nr87ilqat {
  fill: var(--svg-color--806451, #806451);
  d: path("M64.32 37c10.87 0 20.36 2.68 28.36 6.62c-5.81-9.58-16.34-15.97-28.36-15.97c-12.28 0-23 6.69-28.72 16.61C43.61 40.04 53.18 37 64.32 37");
}

.oxpd-u55x {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M64.32 103.32c-34.03 0-53.56-33.13-56.94-39.38c3.07-6.27 20.91-39.26 56.94-39.26s53.87 32.98 56.94 39.26c-3.38 6.25-22.92 39.38-56.94 39.38");
}

.q904vmstc {
  cx: 64.32px;
  cy: 60.79px;
  r: 15.43px;
  fill: var(--svg-color--212121, #212121);
}

.t_s3j0b-f {
  cx: 88.86px;
  cy: 59.37px;
  r: 7.72px;
  fill: var(--svg-color--d9baa5, #d9baa5);
}

.u2w1ocqzb {
  fill: var(--svg-color--b0bec5, #b0bec5);
  d: path("M64.32 27.12c15.81 0 29.84 6.42 41.7 19.09c6.63 7.08 10.73 14.26 12.49 17.67c-4.51 7.99-23.05 36.99-54.19 36.99c-14.88 0-28.63-6.45-40.89-19.17c-6.89-7.15-11.37-14.41-13.3-17.82c1.75-3.41 5.86-10.6 12.49-17.67c11.86-12.67 25.89-19.09 41.7-19.09m0-4.88C22.56 22.24 4.66 64 4.66 64s20.25 41.76 59.66 41.76S123.97 64 123.97 64s-17.9-41.76-59.65-41.76");
}

.vei_7lg5k {
  fill: var(--svg-color--616161, #616161);
  d: path("M7.21 67.21c-.52 0-1.05-.13-1.54-.4a3.207 3.207 0 0 1-1.27-4.35c.85-1.55 21.28-40.21 59.92-40.21s58.47 37.89 59.29 39.41c.84 1.56.27 3.5-1.29 4.35c-1.56.84-3.5.27-4.35-1.29c-.18-.34-18.88-33.86-53.66-33.86c-34.79 0-54.11 34.34-54.3 34.69a3.19 3.19 0 0 1-2.8 1.66");
}

.wtq_tlbqq {
  fill: var(--svg-color--b0bec5, #b0bec5);
  d: path("M64.32 37c26.97 0 45.47 16.51 53.66 27.71c.96 1.31 1.99-4.99 1.12-6.36c-7.84-12.26-25.41-32.91-54.77-32.91S17.38 46.1 9.54 58.36c-.88 1.37.3 6.83 1.41 5.64c8.54-9.17 26.39-27 53.37-27");
}

</style>
