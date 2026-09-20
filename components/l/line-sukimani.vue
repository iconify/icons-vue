<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="xikrlxb8h"/><path class="z25nfeb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:line-sukimani" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xikrlxb8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.64 18.44A12.9 12.9 0 0 1 36.9 24c0 7.125-5.776 12.9-12.9 12.9S11.1 31.126 11.1 24c0-7.124 5.775-12.9 12.9-12.9a12.9 12.9 0 0 1 5.56 1.26");
}

.z25nfeb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.121 10.578a4.3 4.3 0 0 0-3.04 1.26l-9.122 9.12a4.3 4.3 0 1 0 6.081 6.083l9.122-9.123a4.3 4.3 0 0 0-3.041-7.34M24 11.1V2.5M36.9 24h8.6");
}

</style>
