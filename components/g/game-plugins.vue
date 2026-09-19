<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dv20d8b7t"/><path class="tk0oo8bhv"/><path class="ye0e6m0zo"/><circle class="bwzzanbwt"/><path class="ds3qprb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:game-plugins" /></template>
<style>
.bwzzanbwt {
  cx: 30.116px;
  cy: 30.876px;
  r: 4.168px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ds3qprb1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.072 14.508c-.468.376-.58 1.608 1.186 1.798h8.399v2.986");
}

.dv20d8b7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.517 14.46a4.903 4.903 0 1 1 5.555.048M8.14 25.647a4.903 4.903 0 1 1-.24 5.55");
}

.tk0oo8bhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.517 14.46c.33.614.266 1.66-1.29 1.846h-9.65v8.24a1.071 1.071 0 0 0 1.563 1.1m-.239 5.55a.95.95 0 0 0-1.324 1.087v7.93h20.5");
}

.ye0e6m0zo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.806 34.453l2.552 4.44c3.068-1.814 6.202.008 6.202 3.567h5.097c0-3.559 2.838-5.214 6.216-3.559l2.553-4.45c-3.149-1.807-3.151-5.338 0-7.15l-2.553-4.437c-3.035 1.802-6.216.004-6.216-3.572H27.56c0 3.576-3.133 5.374-6.204 3.576l-2.55 4.353c3.228 1.89 3.04 5.485 0 7.232");
}

</style>
