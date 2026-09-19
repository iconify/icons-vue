<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="gkdfu0ngp"/><circle class="two8-pafz"/><path class="zb_jp4lwb"/><circle class="e7xdbccbp"/><circle class="t5ckj9skk"/><circle class="bm-5uhbaw"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ishtar-commander" /></template>
<style>
.bm-5uhbaw {
  cx: 24px;
  cy: 24px;
  r: 18.633px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.e7xdbccbp {
  cx: 24px;
  cy: 24.1px;
  r: 9.317px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gkdfu0ngp {
  cx: 24px;
  cy: 24px;
  r: 7.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t5ckj9skk {
  cx: 24px;
  cy: 24px;
  r: 11.467px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.two8-pafz {
  cx: 24px;
  cy: 24px;
  r: 1.433px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zb_jp4lwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.536 5.08L29.347 16.47m11.971-7.682l-9.913 9.658m.325 10.856l9.685 9.593M29.7 31.47l11.165 11.14M23.94 33.417l.03 2.668m-5.616-4.575L7.399 42.61m8.964-13.174l-9.771 9.556m8.144-13.905l-6.755.014m6.844-2.621l-6.683-.028M16.6 18.44L6.624 8.594m12.203 7.758L7.557 5m16.478 6.34l-.064 3.443M33.16 22.4l6.672.053m-6.566 2.615l6.663.033");
}

</style>
