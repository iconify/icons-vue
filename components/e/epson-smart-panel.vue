<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="hieavyb4h"/><rect class="q6xhqbw7o"/><path class="hmnn5fzuk"/><circle class="od6k6ynxh"/><path class="ugf3gb5zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:epson-smart-panel" /></template>
<style>
.hieavyb4h {
  width: 12.079px;
  height: 20.853px;
  x: 4.5px;
  y: 13.574px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.344px;
  ry: 1.344px;
}

.hmnn5fzuk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.685 26.24h10.48v6.066a1 1 0 0 1-1 1h-8.48a1 1 0 0 1-1-1zm1-10.673h8.48a1 1 0 0 1 1 1v2.985h-10.48v-2.985a1 1 0 0 1 1-1m1.408 13.181h5.664m-5.664 2.521h5.664");
}

.od6k6ynxh {
  cx: 21.651px;
  cy: 22.896px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q6xhqbw7o {
  width: 17.15px;
  height: 6.687px;
  x: 26.35px;
  y: 19.552px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.ugf3gb5zb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.387 32.439h2.305");
}

</style>
