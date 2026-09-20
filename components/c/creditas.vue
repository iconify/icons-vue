<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vswxlnaop"/><path class="zks9wun1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:creditas" /></template>
<style>
.vswxlnaop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 14.75za9.25 9.25 0 0 0-9.25-9.25H9.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h23.75a9.25 9.25 0 0 0 9.25-9.25A9.25 9.25 0 0 0 33.25 24a9.25 9.25 0 0 0 9.25-9.25");
}

.zks9wun1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.526 15.31a12.25 12.25 0 0 0-8.69-3.6c-6.789 0-12.291 5.502-12.291 12.29s5.502 12.29 12.29 12.29c3.394 0 6.467-1.375 8.691-3.6");
}

</style>
