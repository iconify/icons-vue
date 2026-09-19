<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dkka7lb1o"/><path class="u883bt5sk"/><path class="poldtg9ys"/><circle class="ou6js1bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hadesstar" /></template>
<style>
.dkka7lb1o {
  cx: 24px;
  cy: 24px;
  r: 13.3px;
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 1 2;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ou6js1bci {
  cx: 24px;
  cy: 24px;
  r: 11.26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.poldtg9ys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.07 31.06l.33 5.43l-4.13 4l-5.2-.49m10.22-13.77a18 18 0 0 1-1.23 4.85a17.06 17.06 0 0 1-9 9a18 18 0 0 1-4.85 1.24");
}

.u883bt5sk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.4 38.63a16 16 0 0 0 4.56.69a15.34 15.34 0 0 0 10.86-26.19a17 17 0 0 0-3.54-2.64l1.46-2.7A19.6 19.6 0 0 1 37 11a18.35 18.35 0 0 1 5.39 13h3.07A21.48 21.48 0 0 0 24 2.47v3.07a20 20 0 0 1 5.47.82l-.95 2.94A16.4 16.4 0 0 0 24 8.61A15.34 15.34 0 0 0 13.1 34.8a16.4 16.4 0 0 0 3.54 2.64l-1.46 2.71A19.7 19.7 0 0 1 10.93 37a18.35 18.35 0 0 1-5.39-13H2.47A21.49 21.49 0 0 0 24 45.47V42.4a20 20 0 0 1-5.48-.83Z");
}

</style>
