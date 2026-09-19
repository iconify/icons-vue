<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x6xc0wben"/><path class="xr64m415k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fawry" /></template>
<style>
.x6xc0wben {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.888 24c0 3.28-2.088 9.691-2.921 12.118a.316.316 0 0 0 .487.356l15.442-11.36a1.384 1.384 0 0 0 0-2.229L22.454 11.527a.316.316 0 0 0-.487.356C22.8 14.309 24.888 20.72 24.888 24");
}

.xr64m415k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.262 32.201a100 100 0 0 1-1.255 3.917a.316.316 0 0 0 .487.356l15.442-11.36a1.384 1.384 0 0 0 0-2.229L27.494 11.527a.316.316 0 0 0-.487.356c.305.888.778 2.31 1.255 3.917m-9.611 11.133H4.5M6.424 24h12.227m0-2.933h-9.31");
}

</style>
