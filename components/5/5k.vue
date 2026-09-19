<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vu0rxddxe"/><path class="cz7dvnbob"/><path class="otbfcsbji"/><path class="pj9nddc5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:5k" /></template>
<style>
.cz7dvnbob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.9 23.382l.102-6.862l10.273-3.512m13.902 9.982s-4.128-.078-6.488-1.742c-2.497-1.762-7.414-8.24-7.414-8.24");
}

.otbfcsbji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.275 13.008l-5.188 22.585l-11.264-2.157");
}

.pj9nddc5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.681 24.3l6.31 6.687l-.003 12.513");
}

.vu0rxddxe {
  cx: 26.658px;
  cy: 7.118px;
  r: 2.618px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
