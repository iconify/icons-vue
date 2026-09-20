<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="kv2um3bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitpay" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kv2um3bin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.144 25.97a7.01 7.01 0 0 1 6.624-5.63a4.595 4.595 0 0 1 4.638 5.63l-.645 3.66a7.01 7.01 0 0 1-6.624 5.632a4.595 4.595 0 0 1-4.638-5.631m-.993 5.631l3.972-22.524");
}

</style>
