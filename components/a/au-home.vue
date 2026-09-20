<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e_uq19iqh"/><path class="hr131iksp"/><circle class="t4b659o-m"/><path class="puxj31zwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:au-home" /></template>
<style>
.e_uq19iqh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.281 12.683A21.5 21.5 0 0 1 45.501 24c0 11.874-9.626 21.5-21.5 21.5a21.5 21.5 0 0 1-16.36-7.55l-1.14 2.707c-.172.407-.778.284-.778-.157V30.432a2 2 0 0 1 3.86-.736");
}

.hr131iksp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.72 35.317A21.5 21.5 0 0 1 2.5 24C2.5 12.126 12.126 2.5 24 2.5a21.5 21.5 0 0 1 16.359 7.55l1.142-2.707c.171-.407.777-.284.777.157v10.068a2 2 0 0 1-3.86.736");
}

.puxj31zwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.75 28h6.5v6h3.25c.831 0 1.5-.669 1.5-1.5V24h3L24 13L13 24h3v8.5c0 .831.669 1.5 1.5 1.5h3.25z");
}

.t4b659o-m {
  cx: 24px;
  cy: 24px;
  r: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
