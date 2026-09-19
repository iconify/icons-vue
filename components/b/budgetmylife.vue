<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="ivoeacboo"/><path class="epmzy15xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:budgetmylife" /></template>
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

.epmzy15xx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.794 29.31a3.14 3.14 0 0 0 3.062 1.49h2.013a4.26 4.26 0 0 0 4.015-3.4h0a2.752 2.752 0 0 0-2.772-3.4h-2.224a2.752 2.752 0 0 1-2.772-3.4h0a4.26 4.26 0 0 1 4.015-3.4h2.013a3.14 3.14 0 0 1 3.062 1.49m-3.963-1.49l.311-1.7m-3.108 17l.311-1.7M24 36.5v8.999M13.194 17.716l-7.779-4.524m29.449 4.626l7.822-4.451");
}

.ivoeacboo {
  cx: 24px;
  cy: 24px;
  r: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
