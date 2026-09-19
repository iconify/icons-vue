<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n7c84gbmu"/><rect transform="rotate(-45 24 24)" class="ujgfv5der"/><path class="odihvib7d"/><circle class="o-5es3c9h"/><circle class="v5o92qbyu"/><circle class="wdlgccc7n"/><path class="zijftxbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dominos-pk" /></template>
<style>
.n7c84gbmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.371 37.527l-1.958 2.472l1.958 2.488");
}

.o-5es3c9h {
  cx: 30.543px;
  cy: 17.449px;
  r: 2.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.odihvib7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.813 17.819l12.36 12.36");
}

.ujgfv5der {
  width: 35.91px;
  height: 17.47px;
  x: 6.045px;
  y: 15.265px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.9px;
  ry: 0.9px;
}

.v5o92qbyu {
  cx: 21.843px;
  cy: 30.509px;
  r: 2.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wdlgccc7n {
  cx: 13.113px;
  cy: 30.509px;
  r: 2.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zijftxbwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.986 42.492v-4.986h1.588c.898 0 1.626.75 1.626 1.674s-.728 1.675-1.626 1.675h-1.588m4.829-3.345v4.977m.598-2.488h-.598");
}

</style>
