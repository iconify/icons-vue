<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="lnpy-f7il"/><circle class="b53qw6ibd"/><rect class="fkbm8bbaz"/><rect class="meegp7bjb"/><path class="ektyvc9ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droidify-alt-2" /></template>
<style>
.b53qw6ibd {
  cx: 31.551px;
  cy: 12.512px;
  r: 3.776px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ektyvc9ym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.709 16.92a2.996 2.996 0 0 0 4.726 0");
}

.fkbm8bbaz {
  width: 33.785px;
  height: 15.085px;
  x: 7.107px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.135px;
}

.lnpy-f7il {
  cx: 16.427px;
  cy: 12.512px;
  r: 3.776px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.meegp7bjb {
  width: 33.785px;
  height: 18.673px;
  x: 7.107px;
  y: 23.827px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.638px;
}

</style>
