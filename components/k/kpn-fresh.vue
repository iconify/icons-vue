<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="vkr7r1afy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kpn-fresh" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.vkr7r1afy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.395 14.742v8m0-2.786l4.3-5.187m0 7.973l-3.295-4m7.45 4.001v-8h2.619c1.48 0 2.681 1.202 2.681 2.686s-1.2 2.687-2.681 2.687H20.85m9.455 2.626v-8l5.3 8v-8M13.478 33.258v-6.6a1.4 1.4 0 0 1 1.4-1.4h0c.689 0 1.12.204 1.414.585m-4 2.114h2.8m2.248 0v5.301m2.711-5.563c-.904-.365-2.275.351-2.092 1.541c.904.365 2.275-.35 2.092-1.54m4.916 4.552a2 2 0 0 1-1.738 1.01h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v.65h-4m5.595 2.202c.365.307.759.448 1.644.448h.45c.73 0 1.321-.594 1.321-1.325h0c0-.732-.592-1.325-1.322-1.325h-.897c-.73 0-1.322-.594-1.322-1.325h0c0-.732.592-1.325 1.322-1.325h.448c.886 0 1.28.14 1.645.447m1.595-3.147v8m0-3.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v3.3");
}

</style>
