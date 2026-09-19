<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jbaiylb0c"/><path class="sa6z3kv3v"/><circle class="aksmm4b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digismart-consultation-ticket" /></template>
<style>
.aksmm4b7u {
  cx: 10.216px;
  cy: 41.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jbaiylb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.5 14.833c-10.095 2.705-7.748 10.47 1.59 18.718c1.461 1.34 1.91 1.965 1.91 3.74V45.5c10.257 0 19.086-7.246 21.087-17.306S41.704 8.06 32.228 4.136s-20.406-.61-26.104 7.918A21.5 21.5 0 0 0 7.903 38.25");
}

.sa6z3kv3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.5 14.833c10.095 2.705 7.748 10.471-1.59 18.718");
}

</style>
