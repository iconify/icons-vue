<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="junbpjbvj"/><circle class="ob80bkxjz"/><circle class="bfdxdbbtw"/><circle class="pc18swb5w"/><circle class="obt57xbxv"/><circle class="z9k0rgbca"/><circle class="wyfkqq0dg"/><path class="qpeb73n7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arcticonslight" /></template>
<style>
.bfdxdbbtw {
  cx: 24px;
  cy: 5.6px;
  r: 3.1px;
}

.junbpjbvj {
  d: path("m24 10.8l-11.4 6.6v13.2L24 37.2l11.4-6.6V17.4L24 10.8z");
}

.ob80bkxjz {
  cx: 8.1px;
  cy: 14.8px;
  r: 3.1px;
}

.obt57xbxv {
  cx: 39.9px;
  cy: 33.2px;
  r: 3.1px;
}

.pc18swb5w {
  cx: 39.9px;
  cy: 14.8px;
  r: 3.1px;
}

.qpeb73n7w {
  d: path("m12.6 30.6l-1.8 1M24 37.2v2.1m0-28.5V8.7m11.4 21.9l1.8 1m-1.8-14.2l1.8-1m-24.6 1l-1.8-1m11.4 2.4v11h5.6");
}

.wyfkqq0dg {
  cx: 8.1px;
  cy: 33.2px;
  r: 3.1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z9k0rgbca {
  cx: 24px;
  cy: 42.4px;
  r: 3.1px;
}

</style>
