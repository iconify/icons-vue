<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="gbl-tg9wm"/><path class="sh3mzpbnc"/><path class="xp7m0k0ad"/><circle class="raz1dcc3w"/><circle class="xsqzccc6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ami-music" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gbl-tg9wm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.92 22.883c.266-1.438 1.648-2.603 3.086-2.603h0c1.438 0 2.387 1.165 2.12 2.603l-.797 4.296m-3.927-6.899l-1.28 6.899");
}

.raz1dcc3w {
  cx: 35.101px;
  cy: 18.028px;
  r: 0.75px;
  fill: currentColor;
}

.sh3mzpbnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.126 22.883c.267-1.438 1.649-2.603 3.087-2.603h0c1.437 0 2.387 1.165 2.12 2.603l-.797 4.296m4.147-6.899l-1.28 6.899M17.64 24.575c-.266 1.438-1.64 2.604-3.066 2.604h-.907c-.945 0-1.568-.772-1.392-1.725s1.087-1.725 2.032-1.725h3.495");
}

.xp7m0k0ad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.76 20.963c.744-.628 1.194-.683 2.405-.683c1.374 0 2.165.605 1.862 2.239l-.865 4.66");
}

.xsqzccc6b {
  cx: 24px;
  cy: 24px;
  r: 16.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
