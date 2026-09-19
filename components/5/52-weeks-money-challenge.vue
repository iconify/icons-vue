<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q4fhxzbls"/><path class="w1mp8gbui"/><circle class="pyb__jb6w"/><path class="t7y8nfb_a"/><circle class="lyvvvtb2w"/><path class="ny3gjheip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:52-weeks-money-challenge" /></template>
<style>
.lyvvvtb2w {
  cx: 36.58px;
  cy: 24px;
  r: 2.329px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ny3gjheip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.875 33.528v-3.215m10.25 3.215v-3.215");
}

.pyb__jb6w {
  cx: 11.421px;
  cy: 24px;
  r: 2.329px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q4fhxzbls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.364 5.83S3.5 10.489 3.5 14.215c0 2.795 1.864 5.59 1.864 5.59S3.5 24.467 3.5 29.126c0 13.046 15.84 13.046 20.5 13.046s20.5 0 20.5-13.046c0-4.66-1.864-9.318-1.864-9.318S44.5 17.01 44.5 14.216c0-3.727-1.864-8.386-1.864-8.386s-4.659.931-9.318 3.727C28.66 7.693 24.932 7.693 24 7.693s-4.66 0-9.318 1.864C10.022 6.76 5.364 5.83 5.364 5.83");
}

.t7y8nfb_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24.466c-6.523 0-11.182.932-11.182 5.59c0 5.272 2.796 10.183 11.182 10.183s11.182-4.911 11.182-10.182c0-4.66-4.66-5.591-11.182-5.591m16.705-7.523c.931-5.59 1-7.386 1-7.386s-1.864 0-5.591 1.863c0 0 1.795.864 4.59 5.523");
}

.w1mp8gbui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.296 16.943c-.932-5.59-1-7.386-1-7.386s1.863 0 5.59 1.863c0 0-1.795.864-4.59 5.523");
}

</style>
