<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="f1yfyy14d"/><circle class="cjb7gmbqn"/><circle class="chmopnomt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-bubble-chart" /></template>
<style>
.chmopnomt {
  cx: 15.2px;
  cy: 8.8px;
  r: 4.8px;
  fill: currentColor;
}

.cjb7gmbqn {
  cx: 14.8px;
  cy: 18px;
  r: 2px;
  fill: currentColor;
}

.f1yfyy14d {
  cx: 7.2px;
  cy: 14.4px;
  r: 3.2px;
  fill: currentColor;
}

</style>
