<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bdddnpb3y"/><circle class="md2at2bpd"/><path class="ojn0m9bmj"/><path class="pn3j2_vfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jihanpi" /></template>
<style>
.bdddnpb3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.997 17.012a15.532 15.532 0 1 1 22.769 17.471C24.824 38.491 24 42.5 24 42.5s-.823-4.009-7.766-8.017a15.53 15.53 0 0 1-7.237-17.47z");
}

.md2at2bpd {
  cx: 30px;
  cy: 14.033px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ojn0m9bmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28 31.033h-7a6 6 0 0 1-6-6V13.89");
}

.pn3j2_vfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15 21.033s6.667-.822 13.824-2.74");
}

</style>
