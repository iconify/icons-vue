<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="db7xqccqo"/><path class="emb0o6b5w"/><circle class="tg-7m8bzs"/><path class="xb6pacw6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:externer-monitor" /></template>
<style>
.db7xqccqo {
  width: 37px;
  height: 15.5px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.emb0o6b5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.31 26.403h-4.805L26.947 24h-5.894l-1.558 2.403H14.69a2.403 2.403 0 0 0-2.403 2.403v11.291A2.403 2.403 0 0 0 14.69 42.5h18.62a2.403 2.403 0 0 0 2.402-2.403V28.805a2.403 2.403 0 0 0-2.402-2.402");
}

.tg-7m8bzs {
  cx: 24px;
  cy: 34.451px;
  r: 5.106px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xb6pacw6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.029 15.823L24 10.677l2.971 5.146z");
}

</style>
