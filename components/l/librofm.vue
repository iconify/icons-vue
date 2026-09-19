<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nq5pnpz6u"/><path class="jqp0uybgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:librofm" /></template>
<style>
.jqp0uybgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.835 17.298a6.126 6.126 0 0 0-7.827-.02v.02m11.562-4.246a12.045 12.045 0 0 0-15.33 0m19.013-4.458a17.81 17.81 0 0 0-22.72 0");
}

.nq5pnpz6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.81 22.952l12.053-12.053v19.384L26.811 42.336a3.975 3.975 0 0 1-5.622 0L9.137 30.283V10.9l12.052 12.053a3.975 3.975 0 0 0 5.622 0");
}

</style>
