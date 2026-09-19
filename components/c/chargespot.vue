<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="f_z9g9-9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chargespot" /></template>
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

.f_z9g9-9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.969 23.276l3.206-7.227a.43.43 0 0 0-.394-.606h-8.878a.43.43 0 0 0-.418.327L17.77 26.626a.293.293 0 0 0 .285.364h4.01l-2.536 10.731c-.065.276.282.455.469.242l12.36-14.133H27.33a.394.394 0 0 1-.361-.554m1.408.554h17.122");
}

</style>
