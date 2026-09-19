<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yjm1qhb_m"/><path class="t1djshbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:androidvnc" /></template>
<style>
.t1djshbtv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.695 30.133V17.867l8.125 12.266V17.867m-11.194 0l-4.063 12.266L8.5 17.867m31 8.153v.05a4.063 4.063 0 0 1-4.063 4.063h0a4.063 4.063 0 0 1-4.063-4.063v-4.14a4.063 4.063 0 0 1 4.063-4.063h0A4.063 4.063 0 0 1 39.5 21.93v.05");
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
