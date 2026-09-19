<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tzb-4qfqo"/><path class="jc46vbbpf"/><rect class="uk6r5qqop"/><path class="bngdk8bno"/><rect class="v3vmg9g2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:about-you" /></template>
<style>
.bngdk8bno {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.026 25.162v4.871a2.413 2.413 0 0 0 4.826 0v-4.871");
}

.jc46vbbpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.326 25.162l-2.413 3.642L8.5 25.162m2.413 7.284v-3.642m17.255-13.25v4.871a2.413 2.413 0 0 0 4.826 0v-4.871m-14.988 3.642a1.821 1.821 0 0 1 0 3.642h-3.005v-7.284h3.005a1.821 1.821 0 0 1 0 3.642m0 0h-3.005m-2.513 1.205H9.332m-.786 2.416l2.367-7.263l2.368 7.284");
}

.tzb-4qfqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4m25.174-26.946H39.5m-2.413 7.284v-7.284");
}

.uk6r5qqop {
  width: 4.826px;
  height: 7.285px;
  x: 21.517px;
  y: 15.554px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.413px;
  ry: 2.413px;
}

.v3vmg9g2a {
  width: 4.826px;
  height: 7.285px;
  x: 14.375px;
  y: 25.162px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.413px;
  ry: 2.413px;
}

</style>
