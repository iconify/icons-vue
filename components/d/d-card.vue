<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="bas9fvb4o"/><path class="qduos6-6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:d-card" /></template>
<style>
.bas9fvb4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 14h12.037m15.107 0H34.5c2.215 0 4 1.784 4 4v16c0 2.216-1.785 4-4 4h-29m37-13.5h-9.855m-17.007 0H14.5c-2.216 0-4-1.784-4-4v-15");
}

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

.qduos6-6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.645 19.533c0-2.42-2.08-4.38-4.645-4.38s-4.645 1.96-4.645 4.38v2.847c0 2.42 2.08 4.38 4.645 4.38s4.645-1.96 4.645-4.38m0 4.381V9.239M24.808 36v-5.465h1.854c1.048 0 1.898.822 1.898 1.835s-.85 1.836-1.898 1.836h-1.854m1.855 0l1.855 1.793m-10.694-1.832v.022c0 1-.84 1.81-1.876 1.81s-1.876-.81-1.876-1.81v-1.844c0-1 .84-1.81 1.876-1.81s1.876.81 1.876 1.81v.022M30.176 36v-5.465h1.274c1.369 0 2.478 1.07 2.478 2.391v.683c0 1.32-1.11 2.391-2.478 2.391zm-7.606-1.81h-2.509M19.44 36l1.876-5.465L23.192 36");
}

</style>
