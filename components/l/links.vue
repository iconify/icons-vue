<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="pfoiixbsg"/><circle class="r3d_mqsdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:links" /></template>
<style>
.pfoiixbsg {
  cx: 17.745px;
  cy: 16.846px;
  r: 11.346px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r3d_mqsdg {
  cx: 30.255px;
  cy: 31.154px;
  r: 11.346px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
