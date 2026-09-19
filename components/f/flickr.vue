<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="eh81cib2m"/><circle class="ubttozbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flickr" /></template>
<style>
.eh81cib2m {
  cx: 34.14px;
  cy: 24px;
  r: 9.36px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ubttozbrj {
  cx: 13.86px;
  cy: 24px;
  r: 9.36px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
