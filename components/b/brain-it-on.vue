<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="dt-xgbmbi"/><circle class="fv4d30b8u"/><circle class="dafmd5bpq"/><circle class="gtj3ddbss"/><circle class="a7nlp1bhb"/><circle class="p6kqbg4km"/><circle class="pu_2rlirb"/><path class="z8rmw_sso"/></g><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brain-it-on" /></template>
<style>
.a7nlp1bhb {
  cx: 24.061px;
  cy: 27.085px;
  r: 3.178px;
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

.dafmd5bpq {
  cx: 20.142px;
  cy: 32.277px;
  r: 3.178px;
}

.dt-xgbmbi {
  d: path("M20.862 8.124L10.306 30.226l16.572 9.65l14.013-20.089");
}

.fv4d30b8u {
  cx: 14.651px;
  cy: 29.079px;
  r: 3.178px;
}

.gtj3ddbss {
  cx: 25.634px;
  cy: 35.475px;
  r: 3.178px;
}

.p6kqbg4km {
  cx: 29.553px;
  cy: 30.283px;
  r: 3.178px;
}

.pu_2rlirb {
  cx: 33.266px;
  cy: 25.132px;
  r: 3.178px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z8rmw_sso {
  d: path("M19.502 38.653H8.269");
}

</style>
