<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="orm8snb6y"/><circle class="pj5617bmf"/><path class="xwyxj5i-i"/><circle class="kp44ygadn"/><path class="aiqegneto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fdroidkdi" /></template>
<style>
.aiqegneto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20 21.93v9.08");
}

.kp44ygadn {
  cx: 20px;
  cy: 17.74px;
  r: 0.75px;
  fill: currentColor;
}

.orm8snb6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.5 9.5h-29a2.08 2.08 0 0 0-2 2v25a2.08 2.08 0 0 0 2 2h37a2.08 2.08 0 0 0 2-2v-17H37a2.81 2.81 0 0 1-2.5-2.5Z");
}

.pj5617bmf {
  cx: 20px;
  cy: 24px;
  r: 12px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xwyxj5i-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m44.5 19.5l-10-10");
}

</style>
