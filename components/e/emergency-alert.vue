<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a9i47zbev"/><circle class="shxv7ccnn"/><path class="i9afu9blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emergency-alert" /></template>
<style>
.a9i47zbev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.887 14.25a19.5 19.5 0 0 1 0 19.5m-4.696-16.5a13.5 13.5 0 0 1 0 13.5m-4.696-10.5a7.5 7.5 0 0 1 0 7.5M7.113 14.25a19.5 19.5 0 0 0 0 19.5m4.697-16.5a13.5 13.5 0 0 0 0 13.5m4.695-10.5a7.5 7.5 0 0 0 0 7.5");
}

.i9afu9blo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.76 29l2.974-20.5h-9.468L22.24 29z");
}

.shxv7ccnn {
  cx: 24px;
  cy: 35.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
