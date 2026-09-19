<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uijxbdzgh"/><path class="zoc-ljo9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iberia" /></template>
<style>
.uijxbdzgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.15 20.69c5.545-3.107 9.004-5.809 20.648-7.879L44.5 8.685c-14 0-12.405 3.69-22.35 12.005");
}

.zoc-ljo9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 39.315c18.84-22.758 35.79-22.507 38.397-22.952c-5.08 13.83-6.269 22.952-38.397 22.952");
}

</style>
