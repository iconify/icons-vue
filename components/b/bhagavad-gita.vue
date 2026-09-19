<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="b6yjgkcjy"/><path class="k5ybh5y3o"/><circle class="rimu4cckv"/><path class="bceiu4bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bhagavad-gita" /></template>
<style>
.b6yjgkcjy {
  cx: 24px;
  cy: 24px;
  r: 17.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bceiu4bqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.55 20.298l9.037 9.037m-13.536-.971l6.283-6.282m-2.47 10.264l6.367-6.367");
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

.k5ybh5y3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.664 35.262V16.039a3.3 3.3 0 0 1 3.3-3.3h0a3.3 3.3 0 0 1 3.301 3.3v19.223m-8.27-18.168h9.954");
}

.rimu4cckv {
  cx: 18.902px;
  cy: 17.947px;
  r: 3.325px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
