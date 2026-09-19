<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q_cjpbc7w"/><path class="sie2o103f"/><path class="zq1q4_pey"/><circle class="cliq4ac0a"/><circle class="ck5fomb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:3c-aio-toolbox" /></template>
<style>
.ck5fomb1t {
  cx: 35.66px;
  cy: 24.342px;
  r: 0.75px;
  fill: currentColor;
}

.cliq4ac0a {
  cx: 29.936px;
  cy: 24.342px;
  r: 0.75px;
  fill: currentColor;
}

.q_cjpbc7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 28.826v.12c0 5.361-4.346 9.707-9.708 9.707h0c-5.361 0-9.708-4.346-9.708-9.707v-9.892c0-5.361 4.347-9.707 9.708-9.707h0c5.362 0 9.708 4.346 9.708 9.707v.12M5.503 36.181c2.023 1.696 4.208 2.472 9.113 2.472h1.143a7.325 7.325 0 0 0 7.325-7.325h0a7.325 7.325 0 0 0-7.325-7.325");
}

.sie2o103f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 11.794c2.028-1.69 4.214-2.46 9.12-2.447l1.14.006a7.325 7.325 0 0 1 7.324 7.325h0a7.325 7.325 0 0 1-7.325 7.325m-5.63 0h5.63m10.43 1.384a6.604 6.604 0 0 1 13.207 0v3.116a.69.69 0 0 1-.68.688h-11.83a.69.69 0 0 1-.696-.688h0z");
}

.zq1q4_pey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("m37.52 20.777l1.772-1.773m-11.227 1.773l-1.773-1.773");
}

</style>
