<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rlo5j0vsk"/><g class="y9tr6bcfx"><path class="ocdnt1bgp"/><path class="zl5d2yesj"/></g><path class="zkpz4wb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:china-merchants-bank" /></template>
<style>
.ocdnt1bgp {
  d: path("m33.884 32.79l-6.012-14.8l-6.012 14.8z");
}

.rlo5j0vsk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.064 32.79l-6.012-14.8l-6.012 14.8z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zkpz4wb-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24m-10.119-5.448h9.414m-4.402 12.233h3.985M36.217 20.59h9.01m-8.174 2.04h8.403m-7.568 2.038h7.58m-6.744 2.039h6.583m-5.747 2.039h5.386");
}

.zl5d2yesj {
  d: path("m11.07 39.397l-4.537-6.58l11.35-27.701l5.997 14.799l5.997-14.8l11.35 27.702l-4.536 6.58z");
}

</style>
