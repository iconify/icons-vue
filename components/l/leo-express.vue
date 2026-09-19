<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="j-l5s9-fr"/><circle class="pi_wfcj1m"/><circle class="j61vcwbsy"/><path class="z44x7jbri"/><path class="i7o9_yb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:leo-express" /></template>
<style>
.i7o9_yb7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.872 38.015l19.553-11.714h.016m-16.6 16.789l19.367-11.615h.016");
}

.j-l5s9-fr {
  cx: 33.627px;
  cy: 18.937px;
  r: 2.938px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j61vcwbsy {
  cx: 14.355px;
  cy: 7.438px;
  r: 2.938px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pi_wfcj1m {
  cx: 24.098px;
  cy: 13.145px;
  r: 2.938px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z44x7jbri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.332 26.356a2.938 2.938 0 0 1 2.817 5.153M15.818 43.108a2.938 2.938 0 0 1-2.983-5.062");
}

</style>
