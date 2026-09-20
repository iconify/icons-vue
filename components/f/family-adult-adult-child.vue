<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gb7dsabnw"/><path class="gh40vebvi"/><path class="rltc34b1j"/><path class="m1miuc7js"/><circle class="e-qp50b8b"/><path class="skszizbxo"/><circle class="l6luq495q"/><circle class="b9rjd2mpi"/><path class="lf3ceibox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:family-adult-adult-child" /></template>
<style>
.b9rjd2mpi {
  cx: 63.79px;
  cy: 84.81px;
  r: 12.27px;
}

.e-qp50b8b {
  cx: 39.55px;
  cy: 37.88px;
  r: 15.22px;
}

.gb7dsabnw {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.gh40vebvi {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

.l6luq495q {
  cx: 87.97px;
  cy: 37.88px;
  r: 15.22px;
}

.lf3ceibox {
  d: path("M51.6 110.77c-1 0-1.75-.95-1.49-1.91c1.36-4.97 6.95-9.01 13.65-9.01c6.73 0 12.33 3.93 13.67 9.02c.25.96-.49 1.91-1.49 1.91c0-.01-24.34-.01-24.34-.01");
}

.m1miuc7js {
  d: path("M53.72 98.07c-4.01-3.05-6.62-7.85-6.62-13.27c0-8.4 6.25-15.34 14.33-16.49c-.57-7.97-7.08-11.6-18.85-11.6h-7.61c-10.64 0-17.35 4.71-17.35 13.93v25.13c0 3.83 3.11 6.94 6.94 6.94h22.22c5.23.01 6.94-4.64 6.94-4.64");
}

.rltc34b1j {
  fill: var(--svg-color--fff, #fff);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4c-1.9 2.3-2.3 5.6-2.6 8.4c-.2 2.2-2.2 14.9 3.5 11.2c.68-.45 1.23-1.07 1.6-1.8c1.2-2.1 1.9-3.5 3.3-5.6c5.3-8.6 18.8-10.5 18.8-13.5");
}

.skszizbxo {
  d: path("M92.56 56.72h-7.61c-11.77 0-18.28 3.64-18.85 11.6c8.09 1.14 14.35 8.09 14.35 16.49c0 5.41-2.61 10.22-6.62 13.27c0 0 1.7 4.64 6.94 4.64h22.21c3.83 0 6.94-3.11 6.94-6.94V70.65c-.01-9.22-6.73-13.93-17.36-13.93");
}

</style>
