<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="i58ggsbci"/><circle class="m6ltngbxr"/><circle class="xf3e5xb6a"/><circle class="lfmgq0bnn"/><path class="f3e2jq4tx"/><path class="ee_7kzgny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:crowdsource" /></template>
<style>
.ee_7kzgny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.3 31.93c-.105-4.368 9.256-4.576 9.36-.207m-9.36 7.801q4.368.936 9.36 0");
}

.f3e2jq4tx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.3 39.524v-7.801c-.209-1.04-.313-2.705-1.145-4.057c-2.392-3.744-7.488-7.384-10.297-10.4c-1.56-1.769-4.472.935-2.912 2.6l4.472 6.032c3.329 4.68-1.352 9.57 9.881 13.626m9.361 0v-7.801c.208-1.04.312-2.705 1.144-4.057c2.393-3.744 7.49-7.384 10.297-10.4c1.56-1.769 4.577.935 2.913 2.704l-4.473 6.032c-3.328 4.577 1.352 9.465-9.88 13.522");
}

.i58ggsbci {
  cx: 23.98px;
  cy: 10.817px;
  r: 2.808px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lfmgq0bnn {
  cx: 31.469px;
  cy: 16.849px;
  r: 2.808px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m6ltngbxr {
  cx: 23.98px;
  cy: 22.674px;
  r: 2.808px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xf3e5xb6a {
  cx: 16.491px;
  cy: 16.849px;
  r: 2.808px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
