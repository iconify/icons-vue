<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="hk9rb3jwf"/><circle class="za33vwbuw"/><circle class="bqq0uvg-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:egg-inc" /></template>
<style>
.bqq0uvg-b {
  cx: 24px;
  cy: 21.247px;
  r: 0.75px;
  fill: currentColor;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hk9rb3jwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.756 43.16l-2.29-5.01l-.095-7.025m.528-.19l1.854-.611l1.159-2.683l-1.103-2.665l-3.641 2.247l-.668 2.215l.544 2.108Zm1.91-5.959a6.55 6.55 0 0 1 3.146-.153l-3.077-4.495Zm.069-4.648l-3.634-6.399l-5.359-2.28l-4.633-1.167l2.35 5.752l7.27.367Zm-11.276-4.094l-7.515 4.484l-5.486 9.325l-4.66 3.908");
}

.za33vwbuw {
  cx: 24.4px;
  cy: 21.149px;
  r: 1.918px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
