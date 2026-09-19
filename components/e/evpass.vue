<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="aroqe10_c"/><circle class="ue0tod45w"/><path class="i5j2wphef"/><path class="eopdmxb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:evpass" /></template>
<style>
.aroqe10_c {
  cx: 19.342px;
  cy: 31.063px;
  r: 2.825px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eopdmxb1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.198 22.696l1.818 1.819a2.573 2.573 0 0 1 0 3.637h0a2.573 2.573 0 0 1-3.637 0l-1.818-1.819zm-2.74 2.74L3.5 23.478m3.8.116l-1.958-1.958");
}

.i5j2wphef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.167 31.063c4.787.03 10.975 0 10.975 0m5.65 0c3.656 0 5.708-1.636 5.708-3.985c0-3.137-4.416-4.312-8.223-7.018s-6.468-5.948-12.534-5.948c-5.442 0-10.052 3.093-10.052 9.635c0 3.39.774 3.256.774 5.383c0 .818-.045 1.606-1.16 1.606s-2.558-1.8-3.197-2.498");
}

.ue0tod45w {
  cx: 35.967px;
  cy: 31.063px;
  r: 2.825px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
