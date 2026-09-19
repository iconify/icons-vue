<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ijcyk_ern"/><circle class="hdi6y_bdy"/><rect class="lxsk2abjy"/><rect class="q-62pmb0f"/><path class="wlpzxacwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fdroidclassic" /></template>
<style>
.hdi6y_bdy {
  cx: 31px;
  cy: 15.94px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ijcyk_ern {
  cx: 16.98px;
  cy: 15.94px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lxsk2abjy {
  width: 27.32px;
  height: 12.99px;
  x: 10.34px;
  y: 9.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.8px;
}

.q-62pmb0f {
  width: 31.32px;
  height: 20.31px;
  x: 8.34px;
  y: 22.15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.03px;
}

.wlpzxacwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.34 15.94h-1a1 1 0 0 1-1-1v-9.4m29.32 10.4h1a1 1 0 0 0 1-1v-9.4M22.55 6h2.9a1 1 0 0 1 .95.7l.78 2.49h-6.36l.78-2.49a1 1 0 0 1 .95-.7");
}

</style>
