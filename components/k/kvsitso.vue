<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dk5g_sbuu"/><rect class="zdjgj7h-l"/><rect class="l93d5k-5m"/><rect class="qn0a2ku7q"/><rect class="eejdn8bsk"/><rect class="exg9ujdgs"/><rect class="vddf2fb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kvsitso" /></template>
<style>
.dk5g_sbuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 21.468L21.468 5.5m5.161 0L42.5 21.468m-34.274-.097V42.5H39.58V21.371");
}

.eejdn8bsk {
  width: 6.86px;
  height: 6.86px;
  x: 11.44px;
  y: 32.763px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.46px;
}

.exg9ujdgs {
  width: 6.86px;
  height: 6.86px;
  x: 20.495px;
  y: 32.763px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.46px;
}

.l93d5k-5m {
  width: 6.86px;
  height: 6.86px;
  x: 20.495px;
  y: 23.805px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.46px;
}

.qn0a2ku7q {
  width: 6.86px;
  height: 6.86px;
  x: 29.55px;
  y: 23.805px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.46px;
}

.vddf2fb0l {
  width: 6.86px;
  height: 6.86px;
  x: 29.55px;
  y: 32.763px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.46px;
}

.zdjgj7h-l {
  width: 6.86px;
  height: 6.86px;
  x: 11.44px;
  y: 23.805px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.46px;
}

</style>
