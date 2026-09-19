<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="j05ks4bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arrows-portal" /></template>
<style>
.j05ks4bht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.179 21.35l-1.65 5.3l-1.65-5.3l-1.65 5.3l-1.65-5.3m-3.766 0a2 2 0 0 1 2 2v1.3a2 2 0 0 1-2 2h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2m-9.534 2a2 2 0 0 1 2-2m-2 0v5.3m3.767-3.3a2 2 0 0 1 2-2m-2 0v5.3m18.026-.447c.365.307.76.447 1.645.447h.449c.73 0 1.322-.593 1.322-1.325S38.896 24 38.166 24h-.898c-.73 0-1.322-.593-1.322-1.325s.592-1.325 1.322-1.325h.449c.885 0 1.28.14 1.645.447m-26.85 2.853a2 2 0 1 1-4 0v-1.3a2 2 0 1 1 4 0m0 3.3v-5.3");
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

</style>
