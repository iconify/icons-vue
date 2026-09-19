<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hkdpppr2d"/><path class="ws04pybmg"/><path class="xgtru9bdb"/><path class="djkv06btk"/><path class="fr9dlvtsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:china-mobile" /></template>
<style>
.djkv06btk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36 27S26 38 21 38S3 23 3 23");
}

.fr9dlvtsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42 32.5S30 45 24 45S8 34 3 28");
}

.hkdpppr2d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6 15.5S18 3 24 3s16 11 21 17");
}

.ws04pybmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 21s10-11 15-11s18 15 18 15");
}

.xgtru9bdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4 18s10 12 13 12s11-12 14-12s13 12 13 12");
}

</style>
