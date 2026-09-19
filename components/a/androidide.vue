<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g9gtfac6v"/><path class="fl3ruu9ab"/><circle class="ddl1rkb7o"/><circle class="pj25cdclk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:androidide" /></template>
<style>
.ddl1rkb7o {
  cx: 20.859px;
  cy: 24.204px;
  r: 0.75px;
  fill: currentColor;
}

.fl3ruu9ab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.278 30.91c0-6.171 4.827-11.174 10.782-11.174h0c5.955 0 10.783 5.003 10.783 11.174zm18.079-8.229l2.829-2.829m-17.754 2.842l-2.828-2.828");
}

.g9gtfac6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.205 8.609a4.853 4.853 0 0 0-4.853 4.852v5.687A4.853 4.853 0 0 1 5.5 24a4.853 4.853 0 0 1 4.852 4.853v5.686a4.853 4.853 0 0 0 4.853 4.853m17.59-30.783a4.853 4.853 0 0 1 4.853 4.852v5.687A4.853 4.853 0 0 0 42.5 24a4.853 4.853 0 0 0-4.852 4.853v5.686a4.853 4.853 0 0 1-4.853 4.853");
}

.pj25cdclk {
  cx: 27.859px;
  cy: 24.204px;
  r: 0.75px;
  fill: currentColor;
}

</style>
