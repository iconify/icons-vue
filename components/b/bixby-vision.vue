<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="bd_wkeb8q"/><circle class="uskxsktlc"/><path class="j7htlubui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bixby-vision" /></template>
<style>
.bd_wkeb8q {
  cx: 24px;
  cy: 24px;
  r: 1.501px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j7htlubui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.934c8.9 0 19.5-8.18 19.5-13.934S32.9 10.066 24 10.066m0 27.868c-8.9 0-19.5-8.18-19.5-13.934S15.1 10.066 24 10.066");
}

.uskxsktlc {
  cx: 24px;
  cy: 24px;
  r: 8.392px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
