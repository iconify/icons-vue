<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="marqlvbue"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gh-drivers" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.marqlvbue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.963 15.89v16.22M36.5 15.89v16.22m-10.537-8.14H36.5m-14.463-2.707c0-2.967-2.358-5.373-5.268-5.373S11.5 18.296 11.5 21.263v5.474c0 2.967 2.359 5.373 5.269 5.373s5.268-2.406 5.268-5.373H16.77");
}

</style>
