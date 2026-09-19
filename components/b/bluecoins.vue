<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="avn02-1_t"/><path class="r3zzq5bme"/><path class="vwkc1actn"/><path class="mpcnvtlxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bluecoins" /></template>
<style>
.avn02-1_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.024 24.172a8.8 8.8 0 1 0-12.43-.198");
}

.mpcnvtlxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.802 19.798a8.8 8.8 0 1 0-6.286-10.724m13.021 15.282a8.8 8.8 0 1 0 12.42-.529");
}

.r3zzq5bme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.557 28.249a8.8 8.8 0 1 0-6.009 10.883");
}

.vwkc1actn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.28 28.223a8.8 8.8 0 1 0 6.183 10.785M26.4 19.848a8.8 8.8 0 1 0 6.11-10.826");
}

</style>
