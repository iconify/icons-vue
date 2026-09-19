<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p8qcc7z7p"/><rect class="h9_d41erb"/><path class="rpc4jmgvw"/><path class="k37pehcyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:animeworld" /></template>
<style>
.h9_d41erb {
  width: 23.761px;
  height: 18.104px;
  x: 12.358px;
  y: 15.639px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.101px;
}

.k37pehcyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.742 44.022a21.498 21.498 0 1 1 19.85.347");
}

.p8qcc7z7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.933 21.029l-1.831 7.322l-1.83-7.322l-1.831 7.322l-1.831-7.322m-1.215 7.322l-2.38-7.322l-2.471 7.322m.824-2.471h3.203");
}

.rpc4jmgvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.295 33.742v4.833m-5.157 0H29.74m-15.382 5.794a19.235 19.235 0 1 1 19.234 0");
}

</style>
