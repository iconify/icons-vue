<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="myg6apofw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:citizens" /></template>
<style>
.myg6apofw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 26h-9.773A9 9 0 0 1 26 32.732V42.5m-4 0v-9.768A9 9 0 0 1 15.273 26H5.5M26 5.5v9.732A9 9 0 0 1 32.734 22H42.5m-37 0h9.773A9 9 0 0 1 22 15.268V5.5m-16.5 0l12.172 12.172M42.5 5.5L30.345 17.655m-.017 12.673L42.5 42.5M17.672 30.328L5.5 42.5");
}

</style>
