<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vjphzdbdw"/><circle class="p_obkct5z"/><path class="ju3ld-sdd"/><rect class="si68wrbxw"/><path class="tpcl69ban"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:156-poa" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ju3ld-sdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.85 12.947c-.655-.858-1.653-1.447-3.307-1.447h-.276a3.93 3.93 0 0 0-3.93 3.93v4.003");
}

.p_obkct5z {
  cx: 32.267px;
  cy: 19.433px;
  r: 3.93px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.si68wrbxw {
  width: 6.625px;
  height: 10px;
  x: 20.905px;
  y: 26.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.313px;
  ry: 3.313px;
}

.tpcl69ban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.1 33.187h-4.431M29.572 36.5l3.313-10l3.312 10M18.093 22.362c.819.687 1.613 1 3.599 1h.341a3.326 3.326 0 0 0 0-6.652h-3.94V11.5h7.266M11.803 29.832h3.637m-1.157 1.183v-2.366");
}

.vjphzdbdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.803 13.115l2.966-1.615v11.863M11.803 36.5v-10h3.274c1.85 0 3.351 1.504 3.351 3.358s-1.5 3.359-3.351 3.359h-3.274");
}

</style>
