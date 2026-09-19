<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dgoh89bht"/><circle class="oehuelbro"/><path class="ha-z0zuje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ashell-you" /></template>
<style>
.dgoh89bht {
  cx: 19.223px;
  cy: 14.331px;
  r: 1.791px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ha-z0zuje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.491 19.406a1.01 1.01 0 0 0 1-1.102C35.935 11.894 30.555 6.867 24 6.867s-11.933 5.028-12.492 11.437a1.01 1.01 0 0 0 1 1.102zm-24.031 1v10.138c0 6.905 5.402 12.827 12.305 12.954c7.033.129 12.775-5.534 12.775-12.538V20.406a1 1 0 0 0-1-1H12.46a1 1 0 0 0-1 1m5.744-11.537L12.835 4.5m17.961 4.369L35.165 4.5");
}

.oehuelbro {
  cx: 28.777px;
  cy: 14.331px;
  r: 1.791px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
