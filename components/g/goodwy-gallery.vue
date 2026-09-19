<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="beqos-oyf"/><circle class="abndi1bpd"/><circle class="jxh2dfdkf"/><circle class="s8333nfzx"/><circle class="ew91hdc_w"/><circle class="qhvz56b0o"/><circle class="z6zy-4bpc"/><circle class="l7qlt0b-n"/><circle class="df2e07b4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goodwy-gallery" /></template>
<style>
.abndi1bpd {
  cx: 24px;
  cy: 11.373px;
  r: 8.873px;
}

.beqos-oyf {
  cx: 24px;
  cy: 24px;
  r: 6.959px;
}

.df2e07b4c {
  cx: 15.071px;
  cy: 15.071px;
  r: 8.873px;
}

.ew91hdc_w {
  cx: 32.929px;
  cy: 32.929px;
  r: 8.873px;
}

.jxh2dfdkf {
  cx: 32.929px;
  cy: 15.071px;
  r: 8.873px;
}

.l7qlt0b-n {
  cx: 11.373px;
  cy: 24px;
  r: 8.873px;
}

.qhvz56b0o {
  cx: 24px;
  cy: 36.627px;
  r: 8.873px;
}

.s8333nfzx {
  cx: 36.627px;
  cy: 24px;
  r: 8.873px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z6zy-4bpc {
  cx: 15.071px;
  cy: 32.929px;
  r: 8.873px;
}

</style>
