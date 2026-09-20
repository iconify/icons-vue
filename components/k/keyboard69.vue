<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ou8k05byf"/><path class="td_75v8bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keyboard69" /></template>
<style>
.ou8k05byf {
  cx: 24px;
  cy: 10.87px;
  r: 2.77px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.td_75v8bg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 16.11v20.43a3.36 3.36 0 0 1-3.36 3.37A3.35 3.35 0 0 1 37 37.6l-6.28-18.83A3.89 3.89 0 0 0 27 16.11h-3v23.8h-3a3.9 3.9 0 0 1-3.69-2.67l-6.26-18.83a3.36 3.36 0 0 0-3.19-2.3a3.35 3.35 0 0 0-3.36 3.36V39.9");
}

</style>
