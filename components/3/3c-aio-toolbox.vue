<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i53ncf72s"/><path class="dw9gd7r1c"/><path class="zq1q4_pey"/><circle class="cliq4ac0a"/><circle class="ck5fomb1t"/>`;
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

.dw9gd7r1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.503 36.181c2.023 1.696 4.208 2.472 9.113 2.472h1.143a7.325 7.325 0 1 0 0-14.65M5.5 11.794c2.028-1.69 4.214-2.46 9.12-2.447l1.14.006a7.325 7.325 0 1 1 0 14.65m-5.631 0h5.63m10.43 1.384a6.604 6.604 0 0 1 13.207 0v3.116a.69.69 0 0 1-.68.688h-11.83a.69.69 0 0 1-.696-.688s0-3.116 0-3.116");
}

.i53ncf72s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 28.826v.12c0 5.361-4.346 9.707-9.708 9.707c-5.361 0-9.708-4.346-9.708-9.707v-9.892c0-5.361 4.347-9.707 9.708-9.707c5.362 0 9.708 4.346 9.708 9.707v.12");
}

.zq1q4_pey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("m37.52 20.777l1.772-1.773m-11.227 1.773l-1.773-1.773");
}

</style>
