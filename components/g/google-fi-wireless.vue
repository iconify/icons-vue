<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="l-glvhbfi"/><path class="yvzsgzqby"/><circle class="n4yge28ca"/><path class="a5fsrd-jl"/><circle class="hhi0_4b0f"/><path class="a_ti8f4xi"/><circle class="qof_55b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-fi-wireless" /></template>
<style>
.a_ti8f4xi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.774 5.5H11.226c-2.29 0-4.228 1.938-4.228 4.229s1.938 4.228 4.228 4.228h25.548c2.29 0 4.228-1.938 4.228-4.228S39.064 5.5 36.774 5.5");
}

.a5fsrd-jl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.274 26.819h-7.576c-1.938 0-3.7 1.586-3.7 3.524s1.585 3.7 3.7 3.7h7.576c1.938 0 3.7-1.586 3.7-3.7c-.176-1.938-1.762-3.524-3.7-3.524");
}

.hhi0_4b0f {
  cx: 18.098px;
  cy: 30.343px;
  r: 3.545px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l-glvhbfi {
  cx: 10.345px;
  cy: 39.152px;
  r: 3.348px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n4yge28ca {
  cx: 10.874px;
  cy: 20.476px;
  r: 3.876px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qof_55b4n {
  cx: 36.774px;
  cy: 9.729px;
  r: 4.229px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yvzsgzqby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.083 16.6h-16.21c-2.113 0-3.875 1.762-3.875 3.876s1.761 3.876 3.876 3.876h16.033c2.114 0 3.876-1.761 3.876-3.876c.176-2.114-1.585-3.876-3.7-3.876");
}

</style>
