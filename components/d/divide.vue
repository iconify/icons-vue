<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x2xu2umfc"/><circle class="qgie5perq"/><circle class="b-sxirohb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:divide" /></template>
<style>
.b-sxirohb {
  cx: 32px;
  cy: 54.5px;
  r: 7.5px;
  fill: currentColor;
}

.qgie5perq {
  cx: 32px;
  cy: 9.5px;
  r: 7.5px;
  fill: currentColor;
}

.x2xu2umfc {
  fill: currentColor;
  d: path("M2 26h60v12H2z");
}

</style>
