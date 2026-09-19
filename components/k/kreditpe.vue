<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d_c9odbgx"/><circle class="ps0ge-28y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kreditpe" /></template>
<style>
.d_c9odbgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5C13.783 42.5 5.5 34.217 5.5 24V5.5C15.717 5.5 24 13.783 24 24c10.217 0 18.5-8.283 18.5-18.5H24z");
}

.ps0ge-28y {
  cx: 35.1px;
  cy: 35.1px;
  r: 7.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
