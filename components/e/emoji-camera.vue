<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="tqjakabfx"/><path class="f2hftmbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-camera" /></template>
<style>
.f2hftmbqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 15.152h-8.245l-3.217-7.239H16.962l-3.217 7.239H5.5v24.935h37z");
}

.tqjakabfx {
  cx: 24px;
  cy: 26.011px;
  r: 8.043px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
