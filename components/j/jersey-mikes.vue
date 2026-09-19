<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b2vkrkvpn"/><path class="y43g-w3_d"/><path class="yjm1qhb_m"/><path class="fvt0h7y6e"/><circle class="fd0xcnbdp"/><path class="xuprm2boi"/><circle class="x92yb8g6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jersey-mikes" /></template>
<style>
.b2vkrkvpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.256 19.441v2.7c0 1.1-.9 2-2 2c-.6 0-1.1-.2-1.4-.6m-25.112-10.2v6c0 1.1-.9 2-2 2s-2-.9-2-2v-.7m9.98 1.7c-.3.6-1 1-1.7 1c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2v.7h-4m19.651 1.6c-.3.6-1 1-1.7 1c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2v.7h-4");
}

.fd0xcnbdp {
  cx: 19.698px;
  cy: 26.858px;
  r: 0.7px;
  fill: currentColor;
}

.fvt0h7y6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.303 34.258c.4.3.8.4 1.6.4h.4c.7 0 1.3-.6 1.3-1.3s-.6-1.3-1.3-1.3h-.9c-.7 0-1.3-.6-1.3-1.3s.6-1.3 1.3-1.3h.4c.9 0 1.3.1 1.6.4m-19.705-.6v5.4m12.658-1c-.3.6-1 1-1.7 1c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2v.7h-4m-20.259 2.5v-7.9l4 8l4-8v8m7.641-2.9l2.8 2.8m-4-1.6l3.6-3.7m-3.6-2.7v8.1");
}

.x92yb8g6u {
  cx: 35.018px;
  cy: 26.908px;
  r: 0.75px;
  fill: currentColor;
}

.xuprm2boi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.768 28.608c.5-.2.5-.7.5-1v-.7");
}

.y43g-w3_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.256 16.041v3.3c0 1.1-.9 2-2 2s-2-.9-2-2v-3.3m-15.951-.1v5.4m0-3.4c0-1.1.9-2 2-2m2.09 5c.4.3.8.4 1.6.4h.4c.7 0 1.3-.6 1.3-1.3s-.6-1.3-1.3-1.3h-.9c-.7 0-1.3-.6-1.3-1.3s.6-1.3 1.3-1.3h.4c.9 0 1.3.1 1.6.4");
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
