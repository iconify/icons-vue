<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="tu-jq9bdn"/><rect class="bjgmukbgn"/></g><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:decathlon-alt" /></template>
<style>
.bjgmukbgn {
  width: 3.409px;
  height: 5.145px;
  x: 34.887px;
  y: 21.428px;
  rx: 1.704px;
  ry: 1.704px;
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

.tu-jq9bdn {
  d: path("M31.604 21.428v5.144h2.573m-12.009-5.144h3.408m-1.704 5.144v-5.144m15.72 5.144v-5.144L43 26.572v-5.144m-16.222 0v5.144m3.409-5.144v5.144m-3.409-2.582h3.409m-13.647.857v.021c0 .941-.764 1.704-1.705 1.704h0a1.704 1.704 0 0 1-1.704-1.704v-1.736c0-.941.763-1.704 1.704-1.704h0c.941 0 1.704.763 1.704 1.704v.02M9.723 24h1.678m.895 2.572H9.723v-5.144h2.573M5 26.572v-5.144h1.158a2.25 2.25 0 0 1 2.25 2.25v.644a2.25 2.25 0 0 1-2.25 2.25zm15.79-1.721h-2.232m-1.112 1.706l3.344-5.129v5.144");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
