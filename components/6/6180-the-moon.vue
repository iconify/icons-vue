<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="yq5wxkb5w"/><circle class="rksbom0mx"/><path class="conmg24wu"/><rect class="ckyboq04o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:6180-the-moon" /></template>
<style>
.ckyboq04o {
  width: 6.129px;
  height: 9.252px;
  x: 31.371px;
  y: 19.317px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.065px;
  ry: 3.065px;
}

.conmg24wu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.358 20.446c-.51-.669-1.289-1.129-2.578-1.129h-.215a3.065 3.065 0 0 0-3.065 3.065v3.122m14.859-1.447a2.313 2.313 0 0 0-2.313 2.313h0a2.313 2.313 0 0 0 2.313 2.312h1.503a2.313 2.313 0 0 0 2.313-2.312h0a2.313 2.313 0 0 0-2.313-2.313m0 0a2.313 2.313 0 0 0 2.313-2.313h0a2.313 2.313 0 0 0-2.313-2.313H25.36a2.313 2.313 0 0 0-2.313 2.313h0a2.313 2.313 0 0 0 2.313 2.313m-.001 0h1.503");
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

.rksbom0mx {
  cx: 13.565px;
  cy: 25.505px;
  r: 3.065px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yq5wxkb5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.537 20.577l2.313-1.26v9.252");
}

</style>
