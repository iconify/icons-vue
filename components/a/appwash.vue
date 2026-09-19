<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="thjq-kbts"/><path class="qtjc5abys"/><path class="irxvprbmy"/><circle class="y0bkj1lxx"/><circle class="w2khmn1vu"/><path class="mdkybty8y"/><circle class="sd_btxeio"/><circle class="x_15h07fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:appwash" /></template>
<style>
.irxvprbmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.4 8.1H13.6c-.8 0-1.5.6-1.5 1.4v24.9c0 .8.7 1.4 1.5 1.4h20.7c.8 0 1.5-.6 1.5-1.4V9.6c.1-.8-.6-1.5-1.4-1.5");
}

.mdkybty8y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.8 24.2c5.9-2.3 4.4 1.2 10.2.6");
}

.qtjc5abys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 4.5h-25a3 3 0 0 0-3 3v33a3 3 0 0 0 3 3h25a3 3 0 0 0 3-3v-33a3 3 0 0 0-3-3");
}

.sd_btxeio {
  cx: 30.7px;
  cy: 10.9px;
  r: 0.75px;
  fill: currentColor;
}

.thjq-kbts {
  cx: 24px;
  cy: 39.7px;
  r: 0.75px;
  fill: currentColor;
}

.w2khmn1vu {
  cx: 24px;
  cy: 24px;
  r: 5.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x_15h07fl {
  cx: 33px;
  cy: 10.9px;
  r: 0.75px;
  fill: currentColor;
}

.y0bkj1lxx {
  cx: 24px;
  cy: 24px;
  r: 8.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
