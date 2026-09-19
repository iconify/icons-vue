<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="o-a11lb7x"/><rect class="td6ok-bfv"/><circle class="gv6gqib2j"/><circle class="dn9obhqld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:epos" /></template>
<style>
.dn9obhqld {
  cx: 21.1px;
  cy: 17.5px;
  r: 0.75px;
  fill: currentColor;
}

.gv6gqib2j {
  cx: 17.8px;
  cy: 17.5px;
  r: 0.75px;
  fill: currentColor;
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.o-a11lb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.8 28v-8h2.619c1.48 0 2.681 1.203 2.681 2.687s-1.2 2.686-2.681 2.686H16.8m15.758 1.751c.49.639 1.106.877 1.962.877h1.184c1.102 0 1.996-.894 1.996-2s-.894-2-1.996-2h-1.307a2 2 0 0 1-1.997-2c0-1.104.896-2 2.002-2h1.178c.856 0 1.47.237 1.961.876M10.3 24h2.6m1.4 4h-4v-8h4");
}

.td6ok-bfv {
  width: 5.3px;
  height: 8px;
  x: 24.6px;
  y: 20px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

</style>
