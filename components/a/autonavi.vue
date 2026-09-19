<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qwo_gebij"/><path class="jawkgdb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:autonavi" /></template>
<style>
.jawkgdb6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.011 30.09l.865 9.295l2.378-8.269");
}

.qwo_gebij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.011 30.09L5.5 23.01l37-16.394l-8.736 34.768l-15.51-10.268L42.5 6.616Z");
}

</style>
