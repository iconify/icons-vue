<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm9uzjeuh"/><path class="o36a6oz3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dime" /></template>
<style>
.o36a6oz3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.01 32.074l-8.225-14.465l6.143-3.492c5.298-3.013 11.94-1.255 14.894 3.94s1.067 11.801-4.23 14.813l-2.065 1.174m-2.312.77a1.85 1.85 0 0 1-3.214 1.828a1.85 1.85 0 0 1 .693-2.52a1.85 1.85 0 0 1 2.52.692");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
