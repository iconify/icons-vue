<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="k8qpe6bwj"/><circle class="poyw10bpr"/><circle class="lurj52q1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:giant-stopwatch" /></template>
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

.k8qpe6bwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 26.087a4.157 4.157 0 0 0 4.174 4.174a4.03 4.03 0 0 0 4.02-4.174v-4.174a4.126 4.126 0 0 0-4.02-4.174A4.26 4.26 0 0 0 7.5 21.913Zm7.265-6.802l-6.183 9.43m12.937-2.628a4.157 4.157 0 0 0 4.174 4.174a4.03 4.03 0 0 0 4.019-4.174v-4.174a4.126 4.126 0 0 0-4.02-4.174a4.26 4.26 0 0 0-4.173 4.174Zm7.265-6.802l-6.183 9.43m9.706-2.628a4.157 4.157 0 0 0 4.173 4.174a4.03 4.03 0 0 0 4.02-4.174v-4.174a4.126 4.126 0 0 0-4.02-4.174a4.26 4.26 0 0 0-4.173 4.174Zm7.266-6.802l-6.184 9.43");
}

.lurj52q1d {
  cx: 18.702px;
  cy: 20.189px;
  r: 0.75px;
  fill: currentColor;
}

.poyw10bpr {
  cx: 18.702px;
  cy: 27.811px;
  r: 0.75px;
  fill: currentColor;
}

</style>
