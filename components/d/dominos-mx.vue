<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="omz8zom9u"/><rect transform="rotate(-45 24 24)" class="ujgfv5der"/><path class="odihvib7d"/><circle class="o-5es3c9h"/><circle class="v5o92qbyu"/><circle class="aa8mejbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dominos-mx" /></template>
<style>
.aa8mejbzy {
  cx: 13.112px;
  cy: 30.509px;
  r: 2.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.omz8zom9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.002 42.493v-4.995l2.5 5l2.5-4.992v4.993m1.293-4.993l3.213 4.986m.001-4.986l-3.214 4.986");
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

</style>
