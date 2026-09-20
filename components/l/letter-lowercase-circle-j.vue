<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="vtsuf-pip"/><circle class="w-6ipp0zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:letter-lowercase-circle-j" /></template>
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

.vtsuf-pip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.007 18.275v12c0 2.21-1.774 4-3.962 4a3.93 3.93 0 0 1-2.802-1.172");
}

.w-6ipp0zu {
  cx: 27.007px;
  cy: 14.475px;
  r: 0.75px;
  fill: currentColor;
}

</style>
